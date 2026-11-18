Uki: landing page

Live: getuki.online

The landing page for Uki, a personal AI that trains on your phone overnight. While the phone charges, Uki turns your notes, chats and documents into training examples and fine-tunes a small open model on them. By morning it knows your work and writes the way you do, and your data never leaves the device.

One eye sleeps, the other learns.

Uki is at the idea-check stage. This page collects emails for the first 100 beta testers and explains the product, its privacy model, pricing and roadmap.

What the page covers
The problem: cloud assistants send your data to someone else's servers; fine-tuning needs a graphics card, a command line and a ready-made dataset; the real barrier is turning your own texts into training data.
One night with Uki: connect sources → put the phone on charge → automatic clean-up of passwords, card numbers and other people's contacts → auto-dataset → LoRA training on the phone's GPU → a check that rolls the night back if the model got worse → before/after in the morning.
Before/after example: the same request answered by a generic model and by a model trained on your messages.
Privacy: training and inference on the device, an open-source core, offline mode.
Who it is for: freelancers and writers, students, anyone who values privacy.
Pricing (hypotheses for the beta): Free; Pro at $5–8/month; Teams later.
Roadmap: four stages in the first year, each gated by a measurable threshold (for example, at least 70% pick the trained model in a blind test, and a night of training within 6 hours without overheating).
FAQ and a beta sign-up form.
Languages

English, Russian and Kazakh, switched in the header (ENG / РУС / ҚАЗ). All copy lives in a DICT object inside index.html.

Files
index.html    the whole page: markup, styles, translations and script in one file
owl.png       the Uki owl
favicon.png   site icon

No build step and no framework. Fonts come from Google Fonts (Inter, Inter Tight, JetBrains Mono), and the beta form posts to Formspree.

Run locally

Open index.html in a browser, or serve the folder:

bash
python -m http.server 8000
# then open http://localhost:8000
Deploy

Any static host works (GitHub Pages, Netlify, Vercel, Cloudflare Pages): publish the repository root.

Contact

aybaris901@gmail.com

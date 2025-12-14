🧠 AI Resume Builder (ATS-Optimized, One-Page)

An AI-powered resume builder that generates ATS-friendly, one-page resumes using modern LLMs.
The app takes unstructured user input (education, experience, projects, skills) and converts it into professionally written, printable resumes using multiple templates.

👉 No backend required — users can securely provide their own API key.

✨ Key Features

🧾 One-Page A4 Resume Enforcement

Automatically fits content into exactly one A4 page

Smart compact mode for longer resumes

🤖 AI-Generated Content

Converts raw notes into achievement-driven bullet points

Adds quantified impact (percentages, improvements, metrics)

ATS-optimized wording and structure

🎨 Multiple Resume Templates

Modern

ATS Classic (Serif)

Dark Sidebar

Minimal / Olivia-style

🔐 User-Provided API Key

No hard-coded API keys

User enters their own Groq / Cohere / compatible LLM key

Key stored locally using localStorage

🖨️ Print-Perfect PDF Export

Resume rendered inside an iframe

Browser print → pixel-perfect A4 PDF

Colors and layout preserved

⚡ Frontend-Only

Pure HTML, CSS, and JavaScript

No server, no database, no auth required

🧑‍💻 Tech Stack

Frontend:

HTML5

CSS3 (custom, no framework)

Vanilla JavaScript

AI / LLM APIs:

Groq API (LLaMA-3.3-70B compatible)

Cohere Chat API (optional)

Rendering:

iframe-based resume preview

CSS print media queries for A4 export

📸 How It Works

User enters resume details (Education, Experience, Projects, Skills)

User provides their own API key

Selected resume template + AI prompt is sent to LLM

LLM returns clean HTML only

Resume is rendered inside an iframe

User downloads a print-ready PDF

🔑 API Key Handling (Important)

This project does NOT expose any API keys.

Users must enter their own API key

Key is stored locally in the browser using localStorage

The key is never logged or shared

Example:

localStorage.setItem("GROQ_API_KEY", apiKeyInput.value);




🖨️ PDF Export (A4 Guarantee)

Resume is rendered at 210mm × 297mm

CSS enforces:

No overflow

No scrolling

Print-safe colors

Browser print dialog → “Save as PDF”

This ensures compatibility with:

Recruiters

ATS systems

Email submissions

📂 Project Structure
├── index.html
├── style.css
├── script.js
├── README.md

🚀 Getting Started
1️⃣ Clone the repository
git clone https://github.com/your-username/ai-resume-builder.git
cd ai-resume-builder

2️⃣ Open in browser
open index.html


or simply double-click index.html.

3️⃣ Enter:

Resume details

Your LLM API key

Select a template

Click Generate Resume

🧪 Tested On

Chrome (recommended)

Edge

Brave

Firefox (print supported, slight preview differences)

📌 Limitations

Frontend-only (no rate limiting)

API usage depends on user’s own key

Requires internet connection for AI generation

🛠️ Future Improvements

Backend proxy for API security

Job-description keyword matcher

Resume score (ATS compatibility)

Section drag-and-drop reordering

Multi-language resume support



🙌 Acknowledgements

Groq AI

Cohere

Open-source resume formatting standards

ATS best-practice research

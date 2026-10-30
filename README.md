# Skillora AI — Job discovery and resume matching frontend

## Run
1. Extract this ZIP.
2. Open the `skillora_ai` folder in VS Code.
3. Open `index.html` in a browser, or use the VS Code Live Server extension.
4. Internet access is recommended for Google Fonts and image OCR (Tesseract.js CDN).

## Features
- Search across 21 sample roles in technology, data & AI, design, business, marketing and engineering.
- Filter by career field; select a role from a job card or dropdown.
- Paste resume text, upload TXT, or upload a resume image.
- Image OCR uses Tesseract.js in the browser when the CDN is available.
- PDF upload is accepted as an attachment, but this demo asks the user to copy/paste its text.
- Skill-match estimate, strengths, missing skills, improvement suggestions and alternative roles.

## Important limitations
This is a front-end prototype, not a live job board or production AI system.
Job listings and requirements are illustrative sample data, not live vacancies. Resume matching uses keyword detection, not semantic AI, so it may miss synonyms and context. The match score is an estimate, not a hiring probability. Resume text is processed in the browser in this demo. A production version needs a secure backend, PDF parsing, AI model integration, verified job APIs, privacy controls and employer/source links.

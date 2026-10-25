# Fundamental of Nursing Exam Practice — v1.0

A standalone, responsive HTML/CSS/JavaScript educational practice app for GitHub Pages. The 40 questions supplied in the project brief are retained in their original order and wording. This is independent educational practice material, not an official examination or endorsement.

## Files

- `index.html` — application structure
- `styles.css` — responsive styling and colorful results-page resource banner
- `config.js` — app identity, 70% Level 2 threshold, and four commercial links
- `questions.js` — 40-question bank and supplied answer keys
- `app.js` — navigation, answer state, scoring, answer review, sharing, and level unlocking
- `README.md` — project and deployment instructions
- `TEST-CHECKLIST.md` — manual validation checklist
- `TEST-RESULTS.md` — automated checks performed and outstanding tests

## Updated results-page resource banner

The four colorful commercial resource cards are shown inside the Results screen after a level is completed, not on the Home or Quiz screens. Cards use blue, green, orange, and purple styling with directional arrows and responsive desktop, tablet, and mobile layouts. Commercial URLs are preserved exactly as provided.

## Run locally

Open `index.html` in a modern browser. For representative testing of sharing and browser storage, use a local static server or GitHub Pages. No build step or package installation is required.

## Publish on GitHub Pages

1. Create a **new, separate** repository named `fundamental-of-nursing-exam-practice`. Do not modify another application's repository.
2. Upload all eight files to the repository root. Confirm `index.html` is at the root, not inside a nested folder.
3. Open **Settings → Pages**.
4. Select **Deploy from a branch**, choose the default branch (usually `main`) and `/ (root)`, then save.
5. Wait for deployment and open the Pages URL shown in Settings.
6. Test scoring, all four offer links, sharing fallback, and Level 2 unlocking on desktop and mobile.

## Configuration and unlock behavior

Change `unlock.minimumPercent` in `config.js` to configure the passing threshold. Level 2 requires a Level 1 score of at least 70% by default. The gate is client-side and is not secure access control; no server-side validation is implemented.

## Question-bank note

Question wording, option text, order, and answer keys are retained from the supplied prompt. Explanations were not provided and have not been invented. Have a qualified nursing educator review the material before relying on it for clinical exam preparation.

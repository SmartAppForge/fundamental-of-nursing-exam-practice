# Fundamental of Nursing Exam Practice — v1.0

A standalone, responsive HTML/CSS/JavaScript educational practice app designed for GitHub Pages. The app uses the 40 questions and supplied answer keys from the attached prompt in their original order. It is independent practice material, not an official examination or endorsement.

## Project identity

- App name: `Fundamental of Nursing Exam Practice — v1.0`
- Recommended repository: `fundamental-of-nursing-exam-practice`
- Technical ID: `fundamental-of-nursing-exam-practice`
- Domain: `Fundamental of Nursing Exam Practice`
- Audience field as supplied: `Mental Health Disorders and Nursing Student`
- Interface language: English
- Description as supplied: `Reactive app, smart education and moderne learning`

**Source consistency note:** the supplied audience field refers to mental health disorders, while the app title and the supplied questions cover fundamental nursing topics (blood, nursing history, professional duties, ethics, nursing roles, communication, anatomy, and medication routes). The audience value is preserved as supplied rather than silently rewritten.

## Files

- `index.html` — application structure
- `styles.css` — responsive styling
- `config.js` — identity, unlock threshold, and commercial links
- `questions.js` — complete 40-question bank with supplied answer keys
- `app.js` — navigation, answer state, scoring, review, sharing, and unlock logic
- `README.md` — project and publishing instructions
- `TEST-CHECKLIST.md` — validation checklist
- `TEST-RESULTS.md` — honest record of checks performed

## Run locally

Open `index.html` in a modern browser. For representative testing of browser storage and sharing, use a local static server or GitHub Pages. No build step or package installation is required.

## Levels and unlock

- Level 1: questions q1–q20.
- Level 2: questions q21–q40.
- Default Level 2 threshold: 70% on Level 1.
- Change `minimumPercent` in `config.js` to configure the threshold.

Unlock state is stored in the browser's local storage on that device/browser. It is not server-side verification and can be cleared or changed by the user.

## Commercial links

The prompt provides four distinct URLs, so all four are included in `config.js`: practice app, ebook, Ebook + App bundle ($14.98), and Nursing Specialties Master Bundle ($89.98). The links are reproduced exactly as supplied and have not been independently checked for availability or product contents.

## Publish with GitHub Pages

1. Create a **new** GitHub repository named `fundamental-of-nursing-exam-practice`.
2. Upload all eight files so `index.html` is at the repository root.
3. In the repository, open **Settings → Pages**.
4. Select the publishing source/branch and root folder as appropriate, then save.
5. Wait for GitHub Pages to publish the site and open the URL shown in Settings → Pages.
6. Run the checklist in `TEST-CHECKLIST.md` against the published site.

No GitHub repository was created, and no other application or repository was modified.

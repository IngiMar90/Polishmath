# Matematyka krok po kroku

Polish-language mathematics app covering introductory skills roughly aligned with grades 1–6. No account or ChatGPT sign-in is needed. Open `index.html` via GitHub Pages (recommended) or any static web server. The app is installable as a PWA when served over HTTPS.

## What it does

- Starts with an adaptive diagnostic: **three mathematical answers plus "Nie wiem"** per question. It checks each of four strands twice at each tested difficulty; placement is provisional and can be revised by subsequent practice.
- Has 32 Polish-authored lessons with explanatory steps, fully worked examples, guided and independent exercises, hints, and solution feedback. Fresh numbers are generated for repeat practice.
- Tracks progress by a student-entered name locally in the browser. A lesson is marked mastered after at least 7/8 correct and at most two hints. Earlier lessons can always be opened.
- Teacher screen exports JSON backups and a CSV of attempts, and can import a JSON backup. **Local storage is device/browser-specific**: export a backup before clearing browser data or changing devices. The teacher screen is intended for a teacher-supervised device; it has no access control or cloud sync.
- Optional Polish speech uses an installed/browser Polish voice when available. Voice quality and availability vary by device; text remains fully usable without speech.

## Publish on GitHub Pages

In the repository's **Settings → Pages**, select **Deploy from a branch**, `main`, `/ (root)`. The eventual address should be `https://IngiMar90.github.io/Polishmath/`. Pages may take a few minutes to become available after enabling it. On Chrome/Edge, open that URL and use the browser's *Install app* command. No server-side service, subscriptions, or keys are required.

## Limitations and teaching review

The diagnostic is a short placement tool, not a standardized assessment. Multiple choice permits guessing; a correct answer alone does not prove mastery. A Polish-speaking educator should review the vocabulary with the student. The grade numbers are approximate teaching steps, not certified Polish or Icelandic grade equivalences.

# CloudSec Command v4 — CCSK v5 study app

Mobile-first, offline-capable PWA. This build makes CCSK v5 the first track and keeps CCSP and AI security as separate future tracks.

## What's in this build

- 180 original practice questions: 15 per CCSK v5 domain (including original true/false items), with answer rationales, topic tags, and study-guide section references.
- 60-question / 120-minute full mock, 20-question / 40-minute lite mock, 3-question cross-domain micro exam, and one-question / five-minute hourly challenge.
- Domain lessons, text-first bite-size micro-learning, mixed practice and domain drills.
- Local progress tracking, export/import backup, flags, exam history and per-domain accuracy.
- Optional browser notification reminder. The page must remain open for a reliable local timer; closed-app delivery is not guaranteed without a push backend.
- PWA manifest, service worker and install icons.

All practice questions are original app-authored learning items. They are not live exam questions, recalled items or copied third-party questions. The practice bank is not a guarantee of passing. Mock exams follow the domain counts published in the CSA CCSK v5 Knowledge Guide (July 2026): D1 5, D2 5, D3 5, D4 5, D5 4, D6 4, D7 6, D8 7, D9 5, D10 6, D11 5, D12 3. The public exam includes multiple-choice and true/false formats. The full mock uses the published counts; the 20-question lite mock uses a proportional allocation. These are practice distributions, not predictions of live item selection. Each original practice question maps to a section of the uploaded CCSK v5 Study Guide, with the section shown during answer review. The CSA sample questions remain external references and are not included in the bank.

## Publish on GitHub Pages

Upload `index.html`, `bank.js`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`, and this README to the repository root, replacing the existing v3 files. Keep the files together in the same folder. Relative URLs support a GitHub Pages project subpath.

After Pages finishes publishing, open the site in Chrome on Android, refresh, then use Chrome's menu → **Install app** or **Add to Home screen**. The service worker caches the app for offline study after the first successful load. Progress is stored locally in that browser; use **Progress → Export progress** for a backup.

## Study references

Open the References tab for the official CSA Prep Kit, CCSK exam page, Security Guidance v5, CCM/CAIQ, LinkedIn Learning and video resources. Practice questions are freshly written from study-guide concepts and mapped to guide sections. CSA public sample questions remain linked at their source.

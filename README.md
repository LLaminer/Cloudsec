# CloudSec Command v4 — CCSK v5 study app

Mobile-first, offline-capable PWA. This build makes CCSK v5 the first track and keeps CCSP and AI security as separate future tracks.

## What's in this build

- 180 original practice questions: 15 per CCSK v5 domain, with answer rationales and topic tags.
- 60-question / 120-minute full mock, 20-question / 40-minute lite mock, 3-question cross-domain micro exam, and one-question / five-minute hourly challenge.
- Domain lessons, text-first bite-size micro-learning, mixed practice and domain drills.
- Local progress tracking, export/import backup, flags, exam history and per-domain accuracy.
- Optional browser notification reminder. The page must remain open for a reliable local timer; closed-app delivery is not guaranteed without a push backend.
- PWA manifest, service worker and install icons.

All practice questions are original app-authored learning items. They are not live exam questions, recalled items or copied third-party questions. The practice bank is not a guarantee of passing. Mock exams balance questions across domains for practice; CSA does not publish an official domain weighting in the public materials used here.

## Publish on GitHub Pages

Upload `index.html`, `bank.js`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`, and this README to the repository root, replacing the existing v3 files. Keep the files together in the same folder. Relative URLs support a GitHub Pages project subpath.

After Pages finishes publishing, open the site in Chrome on Android, refresh, then use Chrome's menu → **Install app** or **Add to Home screen**. The service worker caches the app for offline study after the first successful load. Progress is stored locally in that browser; use **Progress → Export progress** for a backup.

## Study references

Open the References tab for the official CSA Prep Kit, CCSK exam page, Security Guidance v5, CCM/CAIQ, LinkedIn Learning and video resources. These links remain with their publishers; the app does not reproduce their material.

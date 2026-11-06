# Minimal Pairs Trainer

Hear one of two close words, such as ship and sheep, and pick which one, to sharpen the sounds you say.

Part of the [IELTS Study Suite](https://github.com/Apurba94/ielts-study-suite): 100 free study apps for IELTS. This one is for the IELTS Academic and General Training test. It works offline, as a Windows program or in the browser.

## Download and run

- **Windows:** download `Minimal Pairs Trainer.exe` from the [latest release](https://github.com/Apurba94/ielts-minimal-pairs/releases/latest) and open it. Nothing to install. It opens in its own window and saves your progress in your user folder.
- **Browser:** open it online in the suite's web edition at https://ielts-study-suite.vercel.app/apps/ielts-minimal-pairs/ . Progress stays in that browser.
- **From source:** `python launcher.py` (Python 3.10 or later, no packages needed).

## What it does

Pronunciation is a quarter of your Speaking score, and it is judged on how easily you are understood, not on your accent. Minimal pairs are words that differ in one sound, such as ship and sheep: hearing the difference helps Listening, and saying it helps Speaking. Ten common contrasts for English learners.

Sections: Practice, Pairs, Progress, About.

## How to use it

1. Pick a sound contrast in **Practice**, or All.
2. Press Play and choose the word you heard.
3. Then say both words aloud, slowly, and feel the difference in your mouth.
4. Computer voices are clear but not perfect: if a pair sounds the same, try another voice.

## Good to know

- All questions, passages, recordings and definitions were written for this suite. None are official IELTS questions. For official practice, use the materials on ielts.org and from the test partners.
- It follows IELTS as delivered on computer in 2026. Formats change, so check ielts.org before your test.
- Listening uses the voices installed on your computer, which sound less natural than real test recordings.
- Feedback on writing and speaking counts what a program can count honestly, such as length and linking words. It is not an IELTS band score. Band conversions for Listening and Reading are approximate.
- Not endorsed by or affiliated with the British Council, IDP or Cambridge University Press & Assessment. IELTS is a registered trademark of its owners.

## For developers

The app is plain HTML and JavaScript in `web/`, run by a small Python launcher that serves it on 127.0.0.1 only and needs a secret token for saving. Tests: `node --test "tests/*.test.js"` (29 tests) and `python -m unittest discover -s tests`. Build the .exe with `python build_exe.py`.

Built with AI assistance (Claude Code). MIT licence. By JANIN A APURBA.

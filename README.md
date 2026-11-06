# Shekh Asif — Portfolio

Personal portfolio website of **Shekh Asif**, B.Pharm graduate who also builds WordPress sites, AI projects, graphics and short-form video edits.

**Live site:** https://codewithasifff.github.io/Portfolio-/

## What's on the page
- About, hospital training and skills
- Projects (Jarvis AI assistant, WordPress sites, design and video work)
- **Edits** — 8 short video edits (5 vertical reels + 3 landscape cuts) that autoplay when scrolled into view
- Contact details

## Project structure
| File | Purpose |
|------|---------|
| `index.html` | The whole site (HTML, CSS and JavaScript in one file) |
| `asif.jpg` | Profile photo |
| `vid-01.mp4` … `vid-08.mp4` | Video edits, numbered in the order they appear on the page |
| `edit-01.jpg` … `edit-08.jpg` | Poster (thumbnail) for each video — same number as its video |

Edits 01–05 are vertical (9:16). Edits 06–08 are landscape (16:9).

## Adding or replacing a video
1. Export the video as H.264 MP4 (`.mp4`) and name it `vid-NN.mp4`.
2. Save a thumbnail as `edit-NN.jpg` with the same number and the same shape (vertical or landscape).
3. Add or edit the matching card in the `Edits` section of `index.html`.

## Run locally
Just open `index.html` in a browser. To test it like a real website, run `python -m http.server` in this folder and open http://localhost:8000.

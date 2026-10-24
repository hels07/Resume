# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Stack

A single self-contained `index.html` (CSS and JS inline, images inlined as data URIs) using Three.js and GSAP from a CDN. Chosen by the user in the request. Hosted on GitHub Pages from this repo (`https://hels07.github.io/Resume/`). An `og.jpg` beside it is allowed for link previews only.

## Users

- **College admissions readers** opening the link from Raees's Common App (US and Canadian universities, CS applicants, first deadlines 1 Nov 2026). They have a few minutes per applicant, often on a laptop, and want proof of what he has built and led beyond the transcript.
- **Anyone he sends it to later**: teachers writing recommendations, internship or club contacts, future collaborators. The page has to keep working after the application season.

## Product Purpose

Raees Feysal Temam's personal portfolio. It shows who he is (Year 13, full IB Diploma, at Sandford International School in Addis Ababa since August 2014), what he has built, and what he has led. Success is a reader who finishes the page knowing three or four specific things he made and why, and who can reach him or his code in one click.

## Positioning

A student who notices a problem at school and builds the fix: the school's website, a Connect 4 trainer for his sister, a cafeteria sales forecaster for the canteen queue, a home server from a broken laptop. He wants to study Computer Science, focus on applied machine learning and reinforcement learning, and build things that solve real problems, including back home in Ethiopia.

## Operating Context

- Opened from a link in the Common App (Additional Information or Activities) or shared directly. Desktop first, but must work on a phone.
- Must work as one file. No build step, no server code.

## Capabilities and Constraints

- Contact: email `ftiraees@gmail.com` (confirmed for public display) and GitHub `hels07` (repos moved there from BlazeRayz). No LinkedIn or X account is known; do not invent one.
- **Do not show test scores** (SAT left off by the user's choice). Do not mention the Year 12 Math/Physics grade dip. Do not list the universities he is applying to.
- The school website repo (`hels07/school-website`) is private, so link to its description, not the code. Public repos: `hels07/Connect-4-IA`, `hels07/fb-prophet-forecasting`.
- The cafeteria forecaster is still in development and currently runs on simulated transaction data; say so.

## Brand Commitments

- Name: Raees Feysal Temam. Voice: plain, warm, factual, first person, no hype (matches his brag sheet).
- The user pinned two references: visual design from the @danielsnows Instagram post "SKOTHYA" (night sky, glowing particle tree, gold horizon, IvyPresto Display + Karla, glass cards); layout from YASH's Collect UI portfolio (big name hero with 3D props and fanned project cards, selected work with a toggle, activity graph, stack, experience, contact with copy-email and a "thanks for scrolling" sign-off).
- Tone confirmed: cinematic, with small playful surprises (a few 3D story objects that react to hover or click).
- Lead project confirmed: the Sandford school website.

## Evidence on Hand

- Brag sheet: `C:\Users\rappe\Downloads\Brag Sheet.pdf` (source of truth for activities and numbers).
- Sandford school website: Astro build in `../school-website/web` (screenshots captured from `dist/`). Solo since Year 11, about 200 hours, HTML/CSS/JS/Astro + SEO, close to launch, in discussion with management.
- Connect 4 Puzzle Trainer (IB CS IA): `../Connect-4-IA`. Python, Pygame, Matplotlib; minimax with alpha-beta, odd/even threat module, 15 puzzles verified with Pascal Pons's solver; built for his Year 9 sister.
- Cafeteria sales forecaster: `../fb-prophet-forecasting`. Python, Prophet, pandas, Google Sheets output.
- Digital Society Extended Essay: `C:\Users\rappe\Downloads\IB Digital Society EE.docx`. Elo on 27,909 ATP matches (2016–2026): Elo K=32 63.51% (Brier 0.1323), ATP ranking baseline 64.21%, betting odds 69.43% (n=20,848). Use these numbers only; the older draft's figures are not his.
- Sharks Tales newsletter covers (Feb, Apr, Jun 2026) in `../school-website/web/public/images/newsletter/`.
- Absences: no headshot, no résumé PDF, no LinkedIn, no live URL for the school site. Never fabricate quotes, awards, metrics or links.

## Product Principles

1. Proof over adjectives: show the thing working (play the puzzle, see the site, read the numbers).
2. Every fact traces to the brag sheet, his repos or his EE.
3. One page, readable in three minutes, deep enough for the reader who wants more.
4. Ethiopia and Sandford are home, not a backdrop.

## Accessibility & Inclusion

- Respect `prefers-reduced-motion`; all content readable without WebGL; keyboard reachable; no horizontal scroll from 360 to 1600 px wide.

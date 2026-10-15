# 72nd BPSC Mains Answer Writing & Evaluation Portal

A lightweight static website for running a  BPSC Mains answer writing program. Candidates submit handwritten answer PDFs through a Google Form, join the Telegram group for question drops and discussion, and use the built-in strategy guide to improve their scores.

## Features
- One-click links to the Google Form (PDF submission) and the Telegram group
- Four-step program workflow and PDF/answer-sheet hygiene guidelines
- Three-tab strategy guide: scoring levers, what examiners reward vs. penalise, and paper-wise tips
- Mentor email with a copy-to-clipboard button
- Responsive layout (Tailwind CSS via CDN); no build step or backend

## Setup
1. Open `index.html` and edit the `CONFIG` block near the bottom:
   - `googleFormUrl`: your Google Form link
   - `telegramUrl`: your Telegram invite link
   - `contactEmail`: your mentor/support email
2. Open the file in a browser to test the links.

## Deployment
Host the file as `index.html` on any static host (Cloudflare Pages, Netlify, GitHub Pages).

## Customisation
Edit the strategy guide text, submission rules and branding directly in `index.html`.

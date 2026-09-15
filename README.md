# Anotidaishe A Sanganza — Portfolio Page

A single-page HTML5 portfolio and contact site, built for the CIS2103 Web Technologies Unit II practical assignment at Africa University. This repo will carry forward into the Unit III assignment, which adds responsive CSS3 and Tailwind styling.

## AI Prompt Log

The prompt used to draft the About-section bio, the AI's unedited output, my final revised version, and a short reflection are in [`PROMPT_LOG.md`](./PROMPT_LOG.md).

## Accessibility Issue & Fix

**What my peer reviewer flagged:** My peer reviewer noticed that some of my form inputs didn't have properly associated labels — the visible text near each field wasn't actually linked to the input, so a screen reader couldn't tell what each field was for and clicking the label text didn't focus the field.

**How I fixed it:** I added a `<label for="...">` element for every input, with the `for` attribute matching each input's `id`, so every field in the Contact form is now correctly labelled.

## Files

- `index.html` — the page itself (Parts A, B, D)
- `README.md` — this file
- `PROMPT_LOG.md` — AI prompt, raw output, edited version, reflection (Part C)

## Viewing locally

Clone this repo and open `index.html` in a browser — no build tools needed.

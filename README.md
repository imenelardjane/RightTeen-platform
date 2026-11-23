# RightTeen-platform
**Know your rights. Level up.**
RightTeen explains legal rights to teenagers in plain English, through interactive comic stories, voice and short quizzes, with a clear route to real, free help when they need it.

> Prototype built for the **LegalTech Hackathon in Leeds**.
> RightTeen gives information, **not legal advice**. If someone is in danger, call 999.

## The problem

Young people meet the justice system long before they know their rights.

| | |
|---|---|
| **95,000** | stop and searches of children, 2024-25 |
| **58,300** | arrests of children, 2024-25 |
| **£373** | cost of one night in a young offender institution |
| **76%** | of people who got early advice solved their problem without going to court |

Sources: Youth Justice Statistics 2024-25 (Youth Justice Board), University of York (2010), Access to Justice Foundation (2026).

## What it does

- **Plain-English answers:** young people ask in their own words, with no jargon, and every answer shows its source
- **Interactive stories:** comic scenes from a teenager's real life (the first is "Friday Night", a police stop), with voice narration and sound effects
- **Quizzes:** pick what you would do, then see an explanation of the right that applied
- **Real help:** a route to a human service when a chat is not enough, with links to Childline, Citizens Advice, GOV.UK, ACAS, Shelter and CEOP
- **Topics:** police and school, first home, first job and online life

The prototype has separate pages for **Partners** (charities, helplines, youth clubs), **Schools** and **Students**.

## Safe by design

- Collects as little data as possible: no account or real name needed
- Built around UK GDPR and the ICO Children's Code
- A "Quick exit" button to leave straight away
- A clear route to a human on every screen
- Information and signposting only, never legal advice

## What is in this repo

| File | What it is |
|---|---|
| `index.html` | The RightTeen web prototype, with the audio and images built into one file |

The pages use hash routes (`#/partners`, `#/schools`, `#/students`, `#/dashboard`).

## Run it locally

No install or build step.

1. Download or clone this repository.
2. Open `index.html` in a browser, or use the Live Server extension in VS Code.

An internet connection is needed for the Google Fonts (Baloo 2 and Nunito).

## Built with

- HTML, CSS and vanilla JavaScript, with no frameworks
- A single-file page with embedded audio and images
- Light and dark colour schemes

## Status

Hackathon prototype, with more stories planned.

## Data sources

- Youth Justice Board, Youth Justice Statistics 2024-25
- University of York, 2010
- Access to Justice Foundation, 2026

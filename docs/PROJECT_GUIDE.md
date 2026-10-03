# IP geolocation landing-page experiment: implementation guide

A static landing-page experiment presenting an IP geolocation API concept and associated verification/success pages.

## Scope

**Repository role:** Landing-page experiment.

The default branch includes HTML and a Node manifest but no Express server entry point. Do not present it as an implemented geolocation API or email-verification service.

## Local evaluation

This branch supports a static preview only:

```sh
python -m http.server 4173
```

Open `http://localhost:4173`. The Node dependencies have no corresponding server source or start script in this branch, so `npm install` does not produce a working API.

## Code map

| Path | Responsibility |
| --- | --- |
| `index.html` | Page or browser application entry |

## Walkthrough

Inspect the landing page, verification page, and success page as static UI concepts; no backend setup is available in this branch.

## Verification

No meaningful automated application check was established from the reviewed manifest. Evaluate the walkthrough with synthetic data and record the commit, environment, and result. For a static site, inspect narrow/wide layouts, keyboard focus, links, forms, and console errors.

## Evidence for a case study

Describe this repository as a **landing-page experiment**. A useful case study explains the problem above, traces the walkthrough to its source, names a concrete implementation decision, and records a repeatable evaluation. Separate implemented behavior from roadmap work. Capture screenshots using synthetic data and identify the demonstrated commit.

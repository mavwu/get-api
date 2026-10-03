# IP geolocation landing-page experiment

A static landing-page experiment presenting an IP geolocation API concept and associated verification/success pages.

## Status and scope

The default branch includes HTML and a Node manifest but no Express server entry point. Do not present it as an implemented geolocation API or email-verification service.

## Run or evaluate

This branch supports a static preview only:

```sh
python -m http.server 4173
```

Open `http://localhost:4173`. The Node dependencies have no corresponding server source or start script in this branch, so `npm install` does not produce a working API.

## Example workflow

Inspect the landing page, verification page, and success page as static UI concepts; no backend setup is available in this branch.

## Checks

No meaningful automated application check was established from the reviewed manifest. Evaluate the walkthrough with synthetic data and record the commit, environment, and result. For a static site, inspect narrow/wide layouts, keyboard focus, links, forms, and console errors.

## Implementation notes

See the [implementation guide](docs/PROJECT_GUIDE.md) for the code map, configuration boundary, and evidence to capture for a case study.

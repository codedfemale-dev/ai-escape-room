# AI Escape Room: Exit the Loop

A free browser learning game by [Coded Female](https://codedfemale.com). Escape a fictional AI lab by solving three puzzles about clear instructions, checking evidence and keeping human control over actions.

## Play

GitHub Pages publication is not yet verified. The public play link will be added here after deployment.

## The rooms

1. **The Briefing Bay:** inspect the mission and verified workshop notes, then repair the console’s task, audience and boundaries.
2. **The Evidence Vault:** compare four claims with a source record. Separate supported claims, contradictions and missing information.
3. **The Control Room:** retain relevant facts, reject instructions hidden in source material and choose the action the user authorised.

Each solved room reveals a random code fragment. Use all three to unlock the exit, review the takeaways and download your escape notes. There is no timer or penalty. Each room has two hint levels, including a direct solution for anyone who needs it.

## Run locally

Open `index.html` in a browser, or run `python3 -m http.server 8000` from this folder and visit `http://localhost:8000`. No installation, build step, AI account or API key is required.

## Publish your own copy

Upload the contents of this folder to a GitHub repository. Keep `index.html` at the root and preserve the `assets/` folder. In **Settings → Pages**, select **Deploy from a branch**, `main` and `/ (root)`. Wait for the deployment to finish and verify the published link.

## What this teaches

The game uses scripted examples and curated feedback, not a live AI service. Prompt clarity cannot guarantee accuracy. The prompt injection puzzle illustrates a concept; real AI systems also need technical safeguards. The game is not a security assessment or certification.

All people, events, records and AI responses are fictional. No private information is needed. The game does not use analytics, cookies or browser storage, and no answers are transmitted. Reloading resets progress.

## Brand and accessibility

Uses Coded Female’s established cream, charcoal and muted gold identity with locally served Open Sans and Playfair Display fonts. The lab and little robot are CSS illustrations. The header is a text link, not replacement logo artwork.

Native controls, keyboard focus, a skip link, screen-reader status updates, responsive layout and reduced-motion support are included. Sound is not required. Progress uses text as well as colour.

## Development

- `puzzles.js`: fictional clues, solutions and pure answer evaluation.
- `script.js`: game state, clue inspection, feedback, fragments, exit and notes download.
- `style.css`: layout and illustrations.
- `tests.cjs`: checks for lock logic, clues and page assets. Run `node --test tests.cjs`.

See `VERIFICATION.md` for checks performed and their limits.

## Font licences

The font files are supplied under the SIL Open Font License. See the two OFL files in `assets/`.

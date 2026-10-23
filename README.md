# CEP Scorer

How many of a category's buying situations bring your brand to mind, compared with rivals? Paste the answers from a category entry point (CEP) survey and get each brand's mental market share, mental penetration and network size, plus a map of where each brand over- and under-indexes and your biggest gaps.

Open `index.html` in any browser. No build step, no dependencies, no network calls. Your data stays in your browser.

- **Survey helper:** enter a category and a list of situations, get the questions to ask ("When you are in this situation: ..., which brands come to mind?").
- **Input:** one row per link a person made, `respondent,cep,brand`, plus the number of people surveyed (people who linked nothing do not appear in the rows). The pre-filled data is invented, to show the format.
- **Measures:** mental market share (a brand's share of all links), mental penetration (people who link it to at least one situation, with a Wilson range), network size (situations linked per person who links it), and over- or under-indexing per situation (its share of that situation's links minus its overall share).
- **Verdict:** `ahead`, `behind`, `level` or `too few links`, from 1,000 seeded resamples of the people in your data, comparing you with the best-placed rival.
- **Also shows:** a brand by situation map and your three biggest gaps (situations with a lot of linking where you sit furthest below your usual share).
- **Share:** a paper-ground PNG card, and the URL hash carries your settings and survey questions (not the pasted answers).

Follows the mental availability ideas of Romaniuk and Sharp. Commercial tools may weight things differently, so do not compare numbers across tools. Ask category buyers only, keep the brand list and prompting the same across waves, and treat situation-level gaps as leads on small samples. Pairs with ai-mention-share (the same idea for AI assistants).

## License

Code is MIT licensed ([LICENSE](LICENSE)). The bundled fonts (Bricolage Grotesque, Archivo) are SIL OFL 1.1, with licenses in `fonts/`. The ben.j.ads wordmark and footnote mark in `logo/` are Ben Johnston's brand assets and are not covered by the MIT license.

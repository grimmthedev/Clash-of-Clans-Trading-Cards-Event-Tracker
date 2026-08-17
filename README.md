# Clash of Clans Trading Cards Event Tracker

A simple browser-based tracker for the Clash of Clans Trading Cards event. Keep tabs on your pulls across multiple accounts, spot trade opportunities between them, and track how close each account is to completing the full 60-card set — including cards you could get through trades.

🔗 **Live site:** _add your GitHub Pages link here once published_

## Features

- **Multi-account tracking** — add, rename, or delete accounts and track card counts separately for each one.
- **Live event countdown** — shows time remaining until the event ends.
- **Card search** — quickly look up how many of a specific card each account has.
- **Analysis dashboard:**
  -  **Completion Race** — ranks accounts by progress, including potential completion via trades.
  -  **Safe to Shop** — cards every account has duplicates of, safe to spend in the in-game shop.
  -  **Trade Routes** — highlights cards one account has extra of that another account is missing.
  -  **Missing Completely** — cards none of your accounts have pulled yet.
- All 60 cards across 4 rarity brackets (Elixir, Dark Elixir, Builder Base, Super), with drop rate reference.

## How to use

1. Open the tracker in your browser.
2. Add an account name and select it from the dropdown.
3. Use the `+` / `−` buttons to log how many of each card you've pulled.
4. Check the Analysis Dashboard on the left for trade suggestions and completion progress.

## Notes

- All data is saved locally in your browser (`localStorage`). It is **not** synced across devices or shared between users — each person who opens the tracker starts with their own empty save.
- No account, sign-up, or internet connection required beyond loading the page.
- Built with plain HTML, CSS, and JavaScript — no frameworks, no dependencies.

## License

Released under the [MIT License](LICENSE).

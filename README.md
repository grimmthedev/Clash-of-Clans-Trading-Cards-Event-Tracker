# Clash of Clans Trading Cards Event Tracker

A simple browser-based tracker for the Clash of Clans Trading Cards event. Keep tabs on your pulls across multiple accounts, spot trade opportunities between them, and track how close each account is to completing the full 60-card set.

🔗 **Live site:** https://grimmthedev.github.io/Clash-of-Clans-Trading-Cards-Event-Tracker/

## Features

- **Multi-account tracking** - add, rename, or delete accounts and track card counts separately for each one.
- **Live event countdown** - shows time remaining until the event ends.
- **Card search** - quickly look up how many of a specific card each account has.
- **Analysis dashboard:**
  -  **Completion Race** - ranks accounts by progress, including potential completion via trades.
  -  **Safe to Shop** - cards every account has duplicates of, safe to spend in the in-game shop.
  -  **Trade Routes** - highlights cards one account has extra of that another account is missing.
  -  **Missing Completely** - cards none of your accounts have pulled yet.
- All 60 cards across 4 rarity brackets (Elixir, Dark Elixir, Builder Base, Super), with drop rate reference.

## How to use

### Option 1: Use the Live Site
1. Open the live tracker in your browser.
2. Add an account name and select it from the dropdown.
3. Use the `+` / `-` buttons to log how many of each card you've pulled.
4. Check the Analysis Dashboard on the left for trade suggestions and completion progress.

### Option 2: Run it Locally (Offline)
If you prefer to keep the file directly on your own device, you can easily run it completely offline:
1. Open the `index.html` file in this repository and copy all of the code.
2. Open a plain text editor on your device (like **Notepad** on Windows or **TextEdit** on Mac).
3. Paste the code into the empty document.
4. Save the file as a web page:
   * **On Windows (Notepad):** Click `File` ➔ `Save As...`. At the bottom of the save window, change the **Save as type** dropdown from "Text Documents (*.txt)" to **"All Files (*.*)"**. Name the file exactly `index.html` and click Save.
   * **On Mac (TextEdit):** First, click `Format` ➔ `Make Plain Text` (to remove any rich text formatting). Then click `File` ➔ `Save`, name it exactly `index.html`, and confirm that you want to use the `.html` extension.
5. Double-click your newly saved `index.html` file to open it in any web browser. It will work perfectly with no internet connection required!

## Notes

- All data is saved locally in your browser (`localStorage`). It is **not** synced across devices or shared between users each person who opens the tracker starts with their own empty save.
- No account, sign-up, or internet connection required beyond loading the page.
- Built with plain HTML, CSS, and JavaScript - no frameworks, no dependencies.

## License

Released under the [MIT License](LICENSE).

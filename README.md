# ScoreBug for Fire TV

Every score, always rolling. A full-screen LED-style scoreboard that scrolls through every live game in the sports you pick, plus a scrolling score banner that can run across the top of the screen over whatever you're watching.

- **Scoreboard:** two lanes of games scrolling sideways, in team colors with a lit-dot LED look. One or two games stay still, one on top and one below. Shows down & distance in football and bases, count and outs in baseball. A game flashes when someone scores.
- **Nothing live?** It shows each team's most recent game and final score instead.
- **Fight Night:** UFC and PFL get their own screen instead of scrolling. While a card is on: the two fighters in the cage with records and flags, the round and clock, and live stats side by side (strikes, takedowns, knockdowns, submission attempts, control time), plus every finished bout with how it ended and the rest of the card. With Fight Night as your only sport, between cards it shows the next card: the main event, when it starts, and every bout.
- **Overlay:** a news-style ticker banner across the top (or bottom) of the screen, over any app: a LIVE tag and the live games scrolling past (fights stay on the Fight Night screen). When nothing is live it shows the latest finals.
- **Sports:** NFL, NBA & WNBA, MLB, NHL, college football, college basketball (men's and women's), soccer (MLS, NWSL, Premier League, La Liga, Bundesliga, Serie A, Ligue 1, Champions League) and fight night (UFC, PFL).
- Live games refresh every 2 seconds. Scores come from ESPN's public scoreboards.

Works on its own: you don't need Home Base or any other app.

## What you need

- A Fire TV stick or Fire TV running Fire OS 6, 7 or 8. Newer Vega OS devices can't install it.
- A **Windows computer on the same Wi-Fi**, used once for about 2 minutes.

## Downloads

| | |
|---|---|
| **Downloader code** (on the TV) | **2354632** |
| **[Setup-Fire-TV.bat](https://github.com/Scarpa86/fire-tv-scorebug/releases/latest/download/Setup-Fire-TV.bat)** | One click: installs ScoreBug and allows the overlay |
| **[ScoreBug.apk](https://github.com/Scarpa86/fire-tv-scorebug/releases/latest/download/ScoreBug.apk)** | The app itself, if you'd rather install it another way |

## Set up (step by step)

**On the TV**

1. Turn on Developer Options if you don't see it: **Settings > My Fire TV > About**, highlight the TV's name and press **OK 7 times**.
2. **Settings > My Fire TV > Developer Options > ADB debugging > ON.**

*No computer?* Get **Downloader** from the app store, turn on **Developer Options > Install unknown apps > Downloader**, open Downloader, type **2354632**, choose **Go** and then **Install**. Everything works except the overlay, which Fire TV only lets the computer setup switch on. The first update also asks you to allow ScoreBug to install it.

**On the Windows computer**

3. Download **[Setup-Fire-TV.bat](https://github.com/Scarpa86/fire-tv-scorebug/releases/latest/download/Setup-Fire-TV.bat)**. If the browser warns about the file, choose **Keep**.
4. Double-click it. If Windows shows *"Windows protected your PC"*, click **More info > Run anyway**.
5. It finds the TV by itself. If you have more than one TV, it asks which one: the address is under **Settings > My Fire TV > About > Network**.

**Back on the TV**

6. When the TV asks **"Allow USB debugging?"**, tick **Always allow from this computer** and choose **OK**.
7. Wait for **ALL DONE** on the computer. ScoreBug opens on the TV.

The setup tool is what lets the score banner show over other apps: Fire TV has no settings screen for that permission. Installed another way, everything but the overlay works.

## Using it

- **Pick your sports:** press **Select** on a card to turn it on or off, or use **Select All**.
- **Start Score Bug** opens the full-screen scoreboard. On the scoreboard, **Left / Right** change which way the games scroll, **Up / Down** change the speed, and **Back** returns to the start page.
- If you leave the app while the scoreboard is showing, it opens straight into the scoreboard next time. Handy for a TV or monitor that only shows scores.
- **Overlay:** switch it on, then pick its **position** (top or bottom) and **size**. It runs over other apps and steps aside while ScoreBug itself is open.

## Uninstall

On the TV: **Settings > Applications > Manage Installed Applications > ScoreBug > Uninstall**.

Team names, logos and scores belong to their leagues and ESPN. ScoreBug isn't affiliated with or endorsed by any of them. Fonts: Barlow and Barlow Condensed (SIL Open Font License).

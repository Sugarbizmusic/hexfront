# Hexfront

A classic hex-and-counter WWII wargame for two players in the browser, played hotseat on one screen or by email.

**Fronts**
- **Border War** (base game): Azure League vs Crimson Pact
- **Road to the Rhine** (Europe 1944): Allies vs Axis, with Airborne and Heavy Panzer units
- **Gazala Line** (North Africa 1942): Axis vs Allies, with DAK Panzers, LRDG recon and limited supply range

## Play

Open `index.html` in a browser, or visit the GitHub Pages site for this repository.
On a phone, use **Add to Home Screen** to install it with its own icon.

## Files

| Path | What it is |
|---|---|
| `index.html` | The whole game: rules engine, map and interface |
| `manifest.webmanifest` | App name, colours and icons for Add to Home Screen |
| `icons/` | App icon in SVG and PNG sizes |
| `images/` | Terrain textures, named `{set}_{terrain}_{variant}.jpg` |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

## Play by email

Finish your turn, choose **Send turn** and paste the text into an email. Your opponent opens Hexfront, chooses **Load turn** and pastes it. Dice rolls are stored in the code, so reloading cannot change a roll.

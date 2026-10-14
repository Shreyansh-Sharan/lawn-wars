# LAWN WARS · Family Brawler

A first-person 4v4 family-vs-family suburban brawler: sixty seconds to barricade doors and lay traps, then eight minutes to raid the rival house with garden tools and thrown junk, breaking their tagged valuables for points. Six original heroes with ultimates, ladders to the balcony, two streets (a sunny cul-de-sac and a snowy motor lodge) by day or night, Brawl and a co-op Robot Invasion. Coins, hero levels, perks and house customisation are saved in your browser.

Built with Three.js · First-person · Destructible houses. Part of [Shreyansh Sharan's portfolio](https://shreyanshsharan.com/), split into its own site.

```bash
npm install
npm run dev      # http://localhost:5173
npm run build    # production build in dist/
npm run lint     # oxlint
```

The site is a single page: `#/` is the game's menu, and the same query parameters the portfolio used still work
(for example `#/?auto=...` to skip the menu, `#/?join=CODE` for an invite link).

## Controls

- `W` `A` `S` `D` move · mouse look · `Shift` sprint · `Space` jump · `C` crouch
- `LMB` tap: light swing · hold: heavy swing · `RMB` block (umbrella for Walt) · parry by blocking as a heavy lands
- `G` / `MMB` throw · `E` use: barricade a door, place a trap, pick up a valuable, take a tool · `1`–`3` trap slot
- `F` lean a ladder against a wall (walk into it to climb) · `Q` ultimate · `Esc` release the mouse

## Ads and gear

Optional AdSense and Amazon affiliate IDs come from environment variables (see `.env.example`). Leave them empty and
no ad or shop code loads.

## Credits

Asset sources and licences: [CREDITS.md](CREDITS.md).

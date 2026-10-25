# MOON? Galactic Ecosystem — Website

A static, responsive landing page inspired by modern aerospace and electric-vehicle design. The website is independent and **not affiliated with SpaceX, Tesla, Elon Musk, or NASA**.

## Features
- Silver MOON? coin design rendered in SVG and CSS
- Eight clickable planetary milestones
- Creator-fee allocation model: 60% MOON? burns, 20% proposed holder rewards, 10% MARS? burns, 10% maintenance and creation
- Interactive calculator of gross creator-fee allocations
- Explanation of proposed automation and technical safeguards
- Mobile navigation and FAQ

## Hosting

The site is in `moon/index.html` so the existing Nibbles project is unchanged.

If GitHub Pages is enabled for the repository with branch `main` and folder `/(root)`, the site should be available at:

https://jacobwjaynes11-lgtm.github.io/Nibbles-Coin/moon/

If GitHub Pages isn't enabled yet, select **Settings → Pages → Deploy from a branch → main → /(root)** and save. For a standalone MOON? repository, copy `moon/index.html` to its root and enable Pages there.

## Important limits

This is a front-end concept only. It does **not** collect creator fees, operate a bot, trade tokens, make burns, distribute rewards, or fetch live chain data. There is no deployed contract address configured. Destinations are aspirational market-cap milestones, not guarantees. A production release requires real on-chain infrastructure, fee accounting, key management, swap safety, monitoring and appropriate legal/platform compliance review of holder rewards.

Open `index.html` in a browser to preview. No build step is needed.

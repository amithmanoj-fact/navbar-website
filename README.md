# factors.ai navbar redesign

Working prototype of the new factors.ai navigation, built as plain HTML/CSS/JS so it can be reviewed in a browser and then rebuilt in Webflow.

- `index.html`: the full navbar (desktop menus, mobile menu, animations) in one file
- `assets/factors-logo.svg`: the Factors logo (also inlined in `index.html`)

## Workflow
1. Make each change on its own branch (e.g. `navbar-v2`).
2. Push the branch and open a pull request so the team can see the diff.
3. Merge the version that's approved. The developer rebuilds the merged version in Webflow.

## View it
Open `index.html` in a browser, or turn on GitHub Pages (Settings > Pages > Deploy from a branch > `main`, root folder).

## Notes for the Webflow build
- Links to new pages (Pulse, AdPilot, List Building, 1:1 ABM Campaigns, Creative Studio, Managed ABM, the four Solutions goal pages) use proposed URLs that don't exist yet.
- When AdPilot goes live, redirect `/product/linkedin-adpilot` and `/product/google-adpilot` to `/product/adpilot`.
- Needs a small custom script: the gliding hover highlight, the menu card that resizes between Platform/Services/Solutions, the live Signals feed and the Scout typing card. The ABM chips and Attribution journey can be done with Webflow Interactions.
- Company names in the animated cards (Kitewire, Orbital, Halcyon, etc.) are placeholders.

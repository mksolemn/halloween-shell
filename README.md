# HUB After Dark — The Night Terminal

A Halloween concept for a fuel, fleet, and dispatch software shell: an ornate biomechanical door, a skeletal-hand knocker, a chain-hoisted header, and a rail-mounted sidebar.

**Live demo:** https://mksolemn.github.io/halloween-shell/

## Try it

1. Knock the skeletal hand three times. Quick taps queue the knocks.
2. The door opens and the shell assembles, with synthesized knock, hinge, chain, and carriage sounds.
3. Try the sidebar, **Bleed the line**, and **Replay arrival**.
4. Use **Lock the door** at the bottom of the site to replay the complete entrance.

The knocker also works with Enter or Space. Sound can be muted, and device reduced-motion preferences are respected. Navigation destinations are preview states.

## Hosting

This is a buildless static site. `index.html` contains the complete standalone demo, including embedded artwork and the browser audio engine. There is no application server or build step.

GitHub Pages publishes from the root of `main`. `.nojekyll` disables Jekyll processing. Fonts and the icon library load from public CDNs; the artwork and sound effects are included in the page.

Preferences are stored locally in the visitor's browser. Each fresh visit starts at the locked door.

The entrance fills the browser viewport. The application fills the viewport height and is centered at a maximum width of 1,440px. Short screens can scroll the navigation and content independently.

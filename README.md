Space-War

Space-War is a single-file HTML5 twin-stick arena shooter built with pure HTML, CSS, and JavaScript — no external assets.

It features: waves of enemies (chasers, shooters, splitters), upgrades, dash mechanics, pulse bombs, “juicy” particle effects, and WebAudio. The game is playable on desktop (via keyboard + mouse) and on mobile (via virtual sticks). 
GitHub

Table of Contents

Gameplay / Features

How to Play

Installation / Running Locally

Project Structure

Contributing

License

Credits

Future Ideas / Roadmap

Gameplay / Features

🎯 Waves of enemies — multiple enemy types such as “chasers”, “shooters”, and “splitters”. 
GitHub

🛠️ Upgrades & mechanics — dash mechanic, pulse bombs. 
GitHub

✨ Visual & audio polish — particles effects, WebAudio sound effects, giving a “juicy” game feel. 
GitHub

🌐 Cross-device support:

Desktop: WASD + mouse controls. 
GitHub

Mobile: Virtual sticks for touch input. 
GitHub

📦 No external assets — art, audio, everything is encoded in the HTML/JS/CSS, meaning easy hosting and zero dependency on asset files. 
GitHub

How to Play

On desktop: use WASD (for movement) + mouse (for aiming/shooting). 
GitHub

On mobile: virtual on-screen sticks will appear for movement and aiming/shooting. 
GitHub

Goal: Survive waves of enemies, use upgrades, dashes and bombs to stay alive, rack up score, and enjoy the arcade-style action.

Installation / Running Locally

Clone the repository:

git clone https://github.com/kirubelm1/Space-War.git


Open the game.html file in any modern web browser (Chrome, Firefox, Edge, Safari, etc.).

(Optional) If you want to host online — you can deploy the single HTML file to any static-file hosting (GitHub Pages, Netlify, personal server, etc.).

Because the game is a single HTML file with embedded CSS and JS — there are no build steps, no external dependencies, and no asset management required.

Project Structure
/ (root)
  └── game.html    ← Everything: HTML, CSS, JavaScript in one file


There are no additional directories, assets, or external dependencies.

Contributing

Contributions are welcome! Here are some ways you can help:

Report bugs or submit feature requests by opening an issue.

Submit pull requests for bug fixes, performance improvements, or new features (e.g. new enemy types, power-ups, UI enhancements, mobile controls improvement, etc.).

Improve documentation or add a development roadmap.

Optimize code structure (e.g. modularize JS, add comments, refactor).

If the project grows significantly, consider adding:

a CONTRIBUTING.md file with contribution guidelines.

issue and pull-request templates.

code comments.

tests (if applicable).

a changelog.

These practices follow general open-source documentation guidance. 
fieldguide.opennews.org
+1

License

(If you plan to release under a license — specify it here. If no license yet, consider adding one.)

For example: MIT License — permissive and easy for others to reuse.

Credits

The main author / maintainer: kirubelm1 (as the GitHub repository owner). 
GitHub

Thanks to any contributors (if there are future PRs).

(If you use any external code snippets or assets — list them here.)

Future Ideas / Roadmap

Here are some suggestions for where the project could evolve:

Add save / high-score table (persist scores across sessions via localStorage).

Add multiple levels / increasing difficulty (enemy waves, boss fights, progressive upgrades).

Introduce power-ups (temporary shields, better weapons, speed boosts).

Improve mobile UI/UX — better virtual controls, touch-friendly UI, responsive layout.

Modularize code for easier maintenance (split CSS, JS, HTML; use a build tool or bundler).

Add sound/music toggle, volume controls and more audio polish.

Add a settings menu (fullscreen toggle, control settings, graphics options).

Add documentation website or wiki if project expands.

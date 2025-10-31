# Shopify‑Style Portfolio
A modern personal portfolio website inspired by Shopify’s clean design language. This project dynamically displays my pinned GitHub repositories with live data such as stars, description, language, and last update time. The layout is fully responsive, supports dark/light themes, and uses smooth hover animations for an elegant UX.


## Features
- **Automatic GitHub Integration:** Pulls pinned repositories directly from my GitHub account using the GitHub REST API.
- **Dynamic Cards:** Each project card includes repository details and quick links to GitHub and live demos.
- **Shopify‑Inspired UI:** Two‑tone indigo + tangerine theme with minimalist typography and rounded aesthetics.
- **Dark/Light Mode:** Smart theme detection (auto follows system theme) with persistent manual toggle.
- **Search & Sorting:** Real‑time filtering by name, language, and topics; sorting by stars, update date, or alphabetical order.
- **Hover Animations:** Subtle elevation and glow effects for interactive feedback.


## Tech Stack
- **Frontend:** HTML5, CSS3 (custom variables, transitions, responsive grid)
- **Scripting:** Vanilla JavaScript (ES6+)
- **APIs:** GitHub REST API (for repos + profile avatar)
- **Fonts & Icons:** Google Fonts (Inter), Font Awesome


## Setup
1. Clone the repo or download the files.
```bash
git clone https://github.com/jonb4323/jonb4323.github.io
```
2. Open `index.html` in your browser — no build steps required.
3. To customize:
- Change the `GH_USER` constant to your GitHub username.
- Edit the pinned repo list in `fetchRepos()` or integrate with an API.


## Theming
- Light mode is default.
- Click the toggle icon in the top right side.
- User preference is stored in `localStorage`.


## Future Improvements
- Fetch pinned repos automatically via GraphQL.
- Add analytics for project clicks.
- Add animation to hero elements on scroll.

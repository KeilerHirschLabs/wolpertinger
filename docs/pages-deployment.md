# WOLPERTINGER static website

GitHub Pages publishes only the repository's site/ directory.

- index.html, landing.css and assets/ form the public project landing page. No JavaScript, tracking, sign-in or third-party dependencies.
- The artwork is a concept, not a screenshot of a working UI.
- oauth/callback/ is the existing Frontier sign-in handoff. Its HTML, CSS and JavaScript are independent of the landing page.

Currently reachable callback:
https://keilerhirschlabs.github.io/wolpertinger/oauth/callback/

OAuth registration and application configuration are a separate change. The application source still specifies the earlier personal-account redirect URI. Verify the external Frontier registration and app validation before changing the redirect; publishing this page does not alter either one.

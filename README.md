# to-timeline

Redirects the old address `timeline.hyderabad.urbanobservatory.in` to `https://hyderabad.urbanobservatory.in/timeline/`,
keeping path, query and hash. `404.html` is the same page, so every deep link is caught. GitHub Pages cannot send
server redirects, so this works in browsers only (programs fetching files get this page instead).
Part of the move from subdomains to paths (24 Oct 2026); see `observatory-work/notes/path-migration-plan.md`.

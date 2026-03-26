# Heat Death

Enter a GitHub username. Watch their activity collapse into a star, explode, and freeze into a poster.

**[Play it](https://ashleywolf.github.io/heat-death/)**

A cinematic data visualization. Your repos, followers, and stars become particles -- 500 to 2,000 of them. Gravity pulls them toward center. They swirl, collapse, and form a frozen nebula poster colored by your language palette. Save the 1200x630 PNG.

Optional ambient soundtrack. Toggleable. The whole thing takes about 15 seconds and looks like a screensaver from a better timeline.

## How it works

- GitHub API for profile data (repos, followers, stars, languages)
- Particle count: repo_count x 10 + follower_count x 2 + log(stars)
- Physics: gravity + swirl forces + velocity decay (0.985x)
- Language-based color palette for particles
- Severity tiers based on activity level
- Web Audio API cinematic ambient (optional)
- Canvas 2D with 1200x630 poster export
- Single HTML file, pure browser

# 30-Day Content Calendar Generator

A free, no-signup tool that turns a niche, a set of platforms and a posting pace into a balanced 30-day content calendar. Export it as a CSV and drop it into Notion, Google Sheets or Excel.

**Live demo:** `https://<your-username>.github.io/content-calendar-generator/`

![Screenshot of the calendar](screenshot.png)

## Why I built this

Most small brands do not struggle to post. They struggle to decide what to post, and they end up with a feed that is all promotion or all random. This tool applies the content pillar approach marketers use in planning: every month mixes education, social proof, behind-the-scenes, engagement, promotion and trend content, weighted by what the brand is trying to achieve.

## Features

- Pick one or more platforms: Instagram, LinkedIn, X, Facebook, YouTube, Blog, Email
- Choose 1 to 7 posts per week and a start date
- Goal-based weighting: awareness, leads or sales changes the pillar mix
- No two consecutive posts share a pillar
- Platform-appropriate formats (Reel, Carousel, Thread, Newsletter and more)
- Shuffle for fresh ideas, copy as text, or download a CSV
- Single HTML file, no build step, no dependencies, works offline (apart from the Google Font)

## How it works

1. Pillar weights come from your goal (for example, "sales" gives promotion the largest share).
2. Weighted pillars are shuffled in bags so the mix stays balanced and avoids back-to-back repeats.
3. Topic templates for each pillar are filled in with your niche and audience.
4. Platforms rotate across posting days, and each platform cycles through its own formats.

## Run it locally

Open `index.html` in any browser.

## Deploy on GitHub Pages

Repo Settings, then Pages, then deploy from the `main` branch root.

## Roadmap

- Custom pillar editor
- Holiday and awareness-day overlay
- Drag-and-drop rescheduling
- Companion tool: readability and keyword density checker

## License

MIT

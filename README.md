# halia.spot

A blog built with Astro following the Haxmas Day 11 workshop from Hack Club.

## Getting Started

Install dependencies:
```bash
bun i
```

Start the development server:
```bash
bun dev
```

Visit http://localhost:4321 to see your blog!

## Project Structure

```
src
├── assets
├── components
│   └── FormattedDate.astro
├── content
│   └── posts
│       └── hello-world.md
├── layouts
│   └── BlogPost.astro
├── pages
│   ├── posts
│   │   ├── [...slug].astro
│   │   └── index.astro
│   └── index.astro
├── styles
│   ├── global.css
│   └── post.css
└── content.config.ts
```

## Features

- ✅ Content collections for blog posts
- ✅ Markdown blog posts with frontmatter
- ✅ Homepage with link to posts
- ✅ Posts listing page
- ✅ Individual post pages
- ✅ Formatted dates component
- ✅ Styled with CSS

## Building

Build for production:
```bash
bun run build
```

Preview the production build:
```bash
bun run preview
```

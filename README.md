# Anchored skill

Design resources picked by hand, inside your AI tools.

[Anchored](https://anchored.anchore-d.workers.dev) is a short shelf of tools, books, inspiration, games, articles and podcasts for designers and people who build products. Every pick has a note on why it's worth your time. This skill lets your agent recommend the right few for what you're working on.

## Install

```bash
npx skills add anchored-design/anchored-skill
```

Works with Claude Code and the other agents the [skills](https://github.com/vercel-labs/skills) installer supports.

## Use

```
/anchored I want to build a live portfolio
/anchored my colors look fine as swatches and bad in the product
/anchored something to get better at typography this week
```

You get 3 to 5 picks in the order they're useful, each with the curator's note and a link to its page on Anchored.

## How it works

The skill reads the live list at [picks.json](https://anchored.anchore-d.workers.dev/picks.json) every time, so new picks show up right away and there's nothing to update. It only recommends what's on the shelf.

# Agentic Pelican on a Bicycle

An experiment in agentic iteration on Simon Willison's ["pelican on a bicycle"](https://simonwillison.net/tags/pelican-riding-a-bicycle/) LLM benchmark.

## The Prompt

```
Generate an SVG of a pelican riding a bicycle

- Convert the .svg to .jpg using chrome devtools, then look at the .jpg using your vision
  capabilities.
- Improve the .svg based on what you see in the .jpg and what's still to improve.

- Keep iterating in this loop until you're satisfied with the generated svg.
- Keep the .jpg for every iteration along the way.
```

## Requirements

- Agentic model with vision capabilities, and an agent harness to run the loop
- Chrome DevTools MCP server (for consistent SVG rasterization)

## Results

Each folder contains the iteration sequence for a specific model:
- `claude-opus-4.1/`
- `claude-sonnet-4.5/`
- `claude-haiku-4.5/`
- `gpt-5-medium/`
- `gpt-5-codex-medium/`
- `gemini-2.5-pro/`

## Full Write-up

Read the blog post at: [robert-glaser.de/agentic-pelican-on-a-bicycle](https://www.robert-glaser.de/agentic-pelican-on-a-bicycle)

# Agent Playground

<p>
  <a href="https://galvinlam.github.io/agent-playground/" target="_blank" rel="noopener">
    Open Agent Playground
  </a>
</p>

Agent Playground is a small static browser project for a college portfolio. It presents autonomous agent ideas as a playful simulation: tiny agents move around a sandbox, choose behaviors, react to resources and hazards, and leave a readable timeline of what they are doing.

![Agent Playground screenshot](docs/assets/agent-playground-main.png)

## Open It

No install or build step is required.

1. Open `index.html` directly in a browser.
2. Or serve the folder locally:

```powershell
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## What It Demonstrates

- A canvas-based sandbox with simulated agents.
- Agent status cards that show energy, mood, current behavior, and score.
- Behavior choices such as gather, explore, trade, follow, flee, recharge, cooperate, and compete.
- Scenario buttons that change the environment.
- Strategy sliders and toggles that influence how agents decide what to do.
- A visible timeline/log explaining important decisions in plain language.

## Why It Exists

This project is meant to make autonomous agent experimentation feel approachable. Instead of presenting AI agents as a dense research topic, it shows the core idea visually: agents observe a changing environment, make simple decisions, adapt their behavior, and sometimes work together or compete.

It is intentionally lightweight, static, and easy to screenshot for a portfolio review.

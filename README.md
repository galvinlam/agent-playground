# Agent Playground

<p>
  <a href="https://galvinlam.github.io/agent-playground/" target="_blank" rel="noopener">
    Open Agent Playground
  </a>
</p>

Agent Playground is a browser-based dispatch floor for showing autonomous behavior.

The idea is simple: make agents visible. Five bots move between stations, pick up packets, hand work to each other, recover when energy is low, and explain why they changed plans. It is less like a game board and more like a small operations room where each bot has a job.

![Agent Playground screenshot](docs/assets/agent-playground-main.png)

## What It Shows

- Bots with distinct roles: Collector, Diplomat, Opportunist, Predator, and Survivor.
- A dispatch floor with stations for Inbox, Research, Tools, Memory, Review, Output, and Recharge.
- Packets moving through the system as work gets picked up, delegated, and delivered.
- Scenario modes such as Content Ingest, System Outage, Market Watch, and Research Sprint.
- A decision inspector that shows what an agent observed, how it scored options, what it chose, and why.

## Why It Exists

Autonomous agents are easier to understand when the decision loop is visible. This project turns observe -> score -> choose -> act -> report into something you can watch.

The simulation is intentionally lightweight. It is a visual experiment for agent behavior, not a full planner or production workflow engine.

## Run Locally

No build step is required.

```powershell
python -m http.server 8000
```

Then open `http://localhost:8000`.

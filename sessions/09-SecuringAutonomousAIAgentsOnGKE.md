# Session 9 - Securing Autonomous AI Agents on GKE

- **Speakers**: [Samuel Macharia](https://www.linkedin.com/in/engeniusam/)

## About the session
At Google I/O 2026, Google officially addressed the AI “trust gap” by launching the GKE Agent Sandbox into General Availability. Autonomous LLM agents can now write and execute code on the fly, but running untrusted, user‑generated code in production remains a serious security challenge.

This session goes beyond introductory blog posts to share real‑world engineering experience with the new kubernetes‑sigs/agent‑sandbox framework. Instead of slides, we’ll run a live, end‑to‑end demo of an automated Hackathon Judge Platform deployed on GKE Autopilot. Participants will see raw, untrusted, and even intentionally malicious Python scripts submitted to an LLM grading agent — and how the GKE Agent Sandbox, powered by gVisor, traps code injection attacks, prevents privilege escalation, and isolates workloads seamlessly.

Crucially, we’ll tailor the demo to the African tech ecosystem, where cloud budgets are tight. We’ll show how to configure GKE’s new Pod Snapshots to suspend idle sandboxes to persistent storage — cutting idle compute costs to near zero while still resuming workloads in sub‑second speeds.

## Links
- [📑 Session Slides]()
- [📑 Session GitHub Repository]()
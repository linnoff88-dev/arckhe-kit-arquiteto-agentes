# 🏗️ Agent Architect Kit

**🇧🇷 [Português](README.md) · 🇺🇸 [English](README.en.md) · 🇪🇸 [Español](README.es.md)**

Seven fill-in templates that turn into a **one-page AI agent specification**, plus a simulated rehearsal prompt to test the specification in an AI chat before building anything. A working kit derived from the course [AI Work Architect](https://linnoff88-dev.github.io/arckhe-/) (ARCKHÉ AI PRO).

## 📖 User Guide

Complete guide (landing page + step-by-step instructions): **https://linnoff88-dev.github.io/arckhe-/guia/en/**

## Use

App: **https://linnoff88-dev.github.io/arckhe-/** (single page, no installation, everything is saved in your browser).

The seven blocks:

1. Process and outcome
2. Six-link map (input, decision, action, verification, exception, outcome)
3. Long-horizon request (objective, context, constraints, criteria, approval)
4. Orchestration chain (coordinator, specialists, tools, systems, verification)
5. Context inventory (what it is, where it is, format, access, owner)
6. Quality sheet (conditions with thresholds, stop, call, test suite)
7. Permissions matrix (read, write, modify, send, buy, delete, approve + data outside the scope)

Presets by field ("load example by field" button): **sales** (customer reactivation), **healthcare** (appointment confirmations and insurance claim denials), **accounting** (document and obligation collection), and **law** (deadline tracking). When loaded, the field is marked and the kit points out its specific gaps: patient data outside the scope in healthcare, "the person who enters it doesn't approve it" in accounting, deadlines always requiring a human in law.

Professional workbooks that use these presets: [healthcare](https://linnoff88-dev.github.io/arckhe-/) · [accounting and finance](https://linnoff88-dev.github.io/arckhe-/) · [law](https://linnoff88-dev.github.io/arckhe-/).

Outputs: one-page specification (copy, print/PDF, download `.md`), list of detected gaps, simulated rehearsal prompt, export/import `.json`.

## Structure

- `index.html` — the app (HTML + CSS + JS, self-contained)
- `guia/index.html` — landing page + user guide
- `capa/capa.png` — official cover 1280×720

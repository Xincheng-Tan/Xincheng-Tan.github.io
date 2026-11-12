---
title: "Refuse and Recompute: What a Classical Planner Fixes in LLM Agents"
collection: publications
category: preprints
permalink: /publication/2026-11-12-refuse-and-recompute
excerpt: "LLM agents that act over long horizons under partial observability lose mostly in two ways: an action after which the goal is unreachable, and acting without knowing what must still happen. A classical planner addresses both from the current state, with a guard that refuses such actions and by recomputing the remaining subgoals."
date: 2026-11-12
authors: "<strong>Xincheng Tan</strong>, Ke Wang, Minfeng Zhu<sup>†</sup>"
venue: "Preprint, 2026 · arXiv version coming soon"
citation: "<b>Xincheng Tan</b>, Ke Wang, Minfeng Zhu<sup>†</sup>. Refuse and Recompute: What a Classical Planner Fixes in LLM Agents. Preprint, 2026."
---

Acting over long horizons under partial observability remains a central weakness of LLM agents. In TextWorld Cooking, where actions are irreversible, their losses fall mostly into two classes: actions after which the goal is unreachable, and acting without knowing what must still happen.

A classical planner addresses both from the current state. A guard, sound under partial observability, removes actions after which the goal is unreachable under delete relaxation, and recomputation regenerates the remaining subgoals from a full plan, landmarks, or hand-written rules. In every environment and model where it runs, no guarded episode is lost to an irreversible action of the agent. Where recomputed subgoals help, the gain comes from recomputing them from the current state: issued once, the same subgoals lose most of it. We also introduce CraftIR, a crafting benchmark that separates the two failure classes with two knobs.

Code and data will be released with the arXiv version.

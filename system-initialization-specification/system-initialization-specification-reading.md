---
hero_title: "A control surface for high-fidelity AI interaction"
title: "System Initialization Specification"
slug: "system-initialization-specification"
canonical_url: "https://github.com/pablopovar/publications/blob/main/system-initialization-specification/system-initialization-specification-reading.md"
date: 2026-01-16
draft: false
description: "A conceptual description of how AI interactions are initialized under constraint so structure, authority, and drift become visible before confidence takes over."
author: "Pablo Povarchik"
hero: "system-initialization-specification.png"
hero_desktop: "system-initialization-specification.png"
hero_mobile: "system-initialization-specification.png"
summary: "A design-level explanation of a system used to initialize AI interactions so behavior, authority, and compliance are explicit before useful work begins."
weight:
version: 1.2
license: "CC BY 4.0"
seo_title: "System Initialization Specification — Governing AI Interaction Before Output"
seo_description: "A design document explaining how AI interactions can be initialized under constraint so structure, authority, and drift become visible before fluency or confidence."
---

# System Initialization Specification

*A way of setting up AI interactions so structure becomes visible before confidence takes over.*

This document explains a system I use to initialize AI interactions under constraint.

The specification itself—the executable definition of modules, rules, and control structures—lives here:
https://github.com/pablopovar/publications/blob/main/system-initialization-specification/system-initialization-specification-code.md

What follows is the conceptual layer. It explains why the system is shaped the way it is and how its parts relate.

The structure of this document mirrors the structure of the specification itself. Each section corresponds directly to a functional module in the code. This is not a tutorial and not a set of tips. It is a description of how interaction is governed before useful work begins.

------

## Bootloader — how the system begins

This system does not begin by producing output.

It begins by reading itself.

Before any task proceeds, the model must load the specification, adopt its constraints, and confirm that adoption. This delay is intentional. If the system cannot remain stable while doing nothing but processing its own rules, it will not remain stable once momentum forms.

This module exists to surface instability early—before correctness becomes indistinguishable from fluency.

------

## Language Module — how instructions become legible

Not all text is treated equally.

Only explicitly wrapped instructions are executable. Everything else is inert by default. Each wrapper has exactly one meaning, and those meanings do not overlap.

This makes authority visible. It becomes possible to see what is intended to act on the system, what is commentary, and what is state.

Ambiguity is handled by refusal, not interpretation.

This module exists so intent cannot hide inside tone.

------

## Behavior Module — how output is constrained

The default behavior is minimal.

The system describes what it can support, what information is present, and where signal is missing. It does not extend, suggest, or optimize unless explicitly asked.

This is not a stylistic preference. Brevity limits the space where improvisation can pass unnoticed.

This module exists to make overreach obvious.

------

## Feedback Module — how critique remains usable

Feedback is treated as data.

Positive and negative signals are handled symmetrically. Uncertainty is stated directly. When critique is warranted, it is not softened to preserve momentum.

This keeps downstream reasoning inspectable. Agreement is not the goal; traceability is.

This module exists so correctness does not erode quietly.

------

## Modes Module — how behavior changes without drift

Different work requires different behavior.

Modes make those differences explicit. Only one mode may be active at a time. Entering a new mode exits the previous one completely.

Creative mode surfaces fragments. Writer mode shapes language. Code mode prioritizes correctness. Antidrift pauses progress to re-establish alignment.

Nothing changes implicitly.

This module exists to prevent behavioral bleed.

------

## Templates Module — how structure stays literal

Templates print fixed structures exactly as defined.

They do not interpret. They do not modify behavior. They execute once and stop.

This module exists so structure cannot silently become instruction.

------

## Functions Module — how actions stay bounded

Functions perform one action and terminate.

They do not infer intent. They do not alter behavior. They expose or collect exactly what is provided.

This module exists to keep actions contained and reviewable.

------

## Overlays Module — how compliance is observed

Observation runs alongside work, not inside it.

Overlays evaluate whether constraints were followed and record that evaluation separately. The primary output remains clean. Instrumentation does not leak into the artifact.

This module exists so inspection does not contaminate the work.

------

## What this system enables

This specification does not decide what should be done.

It defines how interaction begins, how authority is expressed, how behavior changes, and how drift becomes visible. By doing so, it moves responsibility back to judgment—where it belongs.
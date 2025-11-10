# 2-Dimensional Grates Research Presentation

This repository contains the LaTeX source files for a presentation on my ongoing research into **2-dimensional grates**, a family of binary matrix configurations defined by local adjacency constraints. The goal of this work is to study how structure emerges from simple placement rules and to uncover counting patterns, recurrence relations, and connections to existing combinatorial sequences.

## What are Grates?

A **grate** is an m×n or n×n binary matrix where each cell containing a 0 must be "supported" by surrounding 1s according to specific local rules. These rules vary depending on the grate type, but they all produce highly structured patterns that can be counted, classified, and related to well-known combinatorial systems.

### Key Grate Types Included in This Research

| Name | Defining Local Rule | Notes |
|------|---------------------|-------|
| **Full Grates** | Every 0 must have a 1 above and to the left | Equivalent to non-attacking kings and certain Fibonacci-derived tiling counts |
| **Plus Grates** | Every 0 must have 1s above, below, left, and right | Introduces central dependency constraints and reduces free choice |
| **X-Grates** | Every 0 must have 1s in diagonal positions | Produces symmetric constraint patterns related to chess-style adjacency |

These grate families show consistent patterns that can be measured and generalized across increasing matrix dimensions.

## Research Goals

- Derive recurrence relations for each grate family.
- Identify closed-form or asymptotic growth behavior where possible.
- Map observed sequences to entries (or new entries) in the **OEIS**.
- Construct visual representations and enumeration tools to explore patterns computationally.
- Create a scalable notation for comparing constraint-based matrix families.

## Presentation Contents

The slide deck walks through:
- Introduction to grates and motivating examples.
- Local rule definitions and constraint propagation.
- Computation methods for counting m×n configurations.
- Visual examples generated from custom Java visualization tools.
- Connections to known combinatorial sequences.
- Current open questions and research directions.

## How to Build the Presentation

You will need a working LaTeX installation/Viewer such as:

- TeX Live
- MiKTeX
- Overleaf

Cite and related work

OEIS references and related sequences are cited in-deck where relevant.

If you reuse the figures or data tables, please include attribution to this repository including a citation of my name.

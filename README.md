# 2-Dimensional Grates Research Presentation

This repository contains the LaTeX source files for a presentation on my ongoing research into **2-dimensional grates**, a family of binary matrix configurations defined by local adjacency constraints. The goal of this work is to study how structure emerges from simple placement rules and to uncover counting patterns, recurrence relations, and connections to existing combinatorial sequences.

### [Presentation Rec.](https://mathcolloquium.sites.ccsu.edu/past/Fall2025/ZLariccia-103125.mp4)
### [Abstract](/GratesAbstractCOLL.pdf)
### [NES MAA (Mathematical Association of America Talk 11/21/2025](/NESMAA+Fall+2025+Cnference+Program+-+Sacred+Heart.pdf)
### [PDF of Presentation](https://github.com/zachsarc/LaTex_Presi/releases/tag/v1.0)


## What are Grates?

A **grate** is an m×n or n×n binary matrix where each cell containing a 0 must be "supported" by surrounding 1s according to specific local rules. These rules vary depending on the grate type, but they all produce highly structured patterns that can be counted, classified, and related to well-known combinatorial systems.

### Key Grate Types Included in This Research

| Name | Defining Local Rule | Notes |
|------|---------------------|-------|
| **Full Grates** | Every 0 must have a 1 above, below, to the left, right, diagonally, and anti-diagonally | Equivalent to non-attacking kings and certain Fibonacci-derived tiling counts |
| **Plus Grates** | Every 0 must have 1s above, below, left, and right | Introduces central dependency constraints and reduces free choice |
| **X-Grates** | Every 0 must have 1s in diagonal positions | Produces symmetric constraint patterns related to chess-style adjacency |

These grate families show consistent patterns that can be measured and generalized across increasing matrix dimensions.

## Research Goals

- Derive recurrence relations for each grate family.
- Identify closed-form or asymptotic growth behavior where possible.
- Map observed sequences to entries (or new entries) in the **OEIS**.
- Construct visual representations and enumeration tools to explore patterns computationally.
- Create a scalable notation for comparing constraint-based matrix families.

## Repos for each program and their corresponding descriptions (Repos will be coming, just have to license them)

| Name                               | Description                                                                                                 |
| ---------------------------------- | ----------------------------------------------------------------------------------------------------------- |
| mxn-Plus-Grate-Counter-Reformatted | Counts m×n plus-grate configurations using a cleaner, reorganized codebase for readability and maintenance. |
| nxn-Full-Grate-Visualizer          | Java visualizer for exploring n×n full-grate binary matrices with interactive rendering of valid patterns.  |
| nxn-Full-Grate-Determinant         | Computes n×n full-grate counts using a determinant/linear algebra approach (transfer-matrix style method).  |
| nxn-Plus-Grate-Counter             | Counts n×n plus-grate configurations based on plus-constraint rules using efficient enumeration techniques. |
| nxn-Plus-Grate-Counter-Reformatted | Refactored n×n plus-grate counter with improved structure, naming, and code clarity.                        |
| mxn-Plus-Grate-Counter-Optimized   | Performance-optimized m×n plus-grate counter using faster state handling and reduced computation overhead.  |
| nxn-Full-Grate-Counter             | Counts n×n full-grate configurations in Java using structured combinatorial counting logic.                 |
| mxn-X-Grate-Counter-Optimized      | Optimized counter for m×n X-grate configurations with speed-focused improvements to the counting pipeline.  |
| mxn-Full-Grate-Counter-Optimized   | Faster m×n full-grate counter with optimizations like streamlined transitions and better state reuse.       |
| mxn-X-Grate-Visualizer             | Visualizer for m×n X-grate patterns, letting you generate and view valid configurations.                    |
| nxn-X-Grate-Visualizer             | Visualizer for n×n X-grate configurations with a simple Java UI to inspect valid grids.                     |
| mxn-X-Grate-Counter                | Counts m×n X-grate configurations, producing totals for grids under the X-style constraint rules.           |
| nxn-X-Grate-Counter                | Counts n×n X-grate configurations using a structured counting approach for square grids.                    |
| mxn-Plus-Grate-Visualizer          | Java visualizer for m×n plus-grate configurations to preview and inspect valid matrices.                    |
| nxn-Plus-Grate-Visualizer          | Java visualizer for n×n plus-grate configurations with interactive display of valid grids.                  |
| mxn-Plus-Grate-Counter             | Counts m×n plus-grate configurations, producing totals for rectangular grids under plus constraints.        |
| mxn-Full-Grate-Visualizer          | Java visualizer for m×n full-grate configurations to explore and display valid patterns.                    |
| mxn-Full-Grate-Counter             | Counts m×n full-grate configurations and outputs totals for rectangular grid sizes.                         |

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

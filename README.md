# gentleman-lwb25

This repository showcases an implementation of the Questionnaire Language (QL) using Gentleman, a lightweight web‑based projectional editor. 
The goal is to demonstrate how concepts (metamodel) and projections (concrete syntax) in Gentleman can be composed to model, render, validate, and execute dynamic questionnaires with conditional logic and computed fields.

## Context

### About Gentleman

Gentleman is a lightweight web‑based projectional editor that aims to make modeling more accessible to domain experts and practitioners (outside traditional software engineering). The editor surface is a composition of projections (graphical, tabular, textual, and interactive widgets) bound to concepts that structure the model data. Instead of relying on parsing text into an abstract syntax tree (AST), Gentleman directly edits the AST through projections. This eliminates syntax errors and supports a wide range of notations—textual, graphical, tabular, and interactive widgets.
Gentleman emphasizes simplicity and flexibility. Its minimalistic web-based design reduces visual clutter and focuses attention on the modeling activity itself. By being distributed as a JavaScript library, it can be embedded in any web application, enabling smooth integration into existing workflows. Projections can be styled, customized, and reused, making the tool adaptable to various domains and user needs.

### About the LWB Challenge & the QL task

The Language Workbench Challenge, initiated in 2013, aims to demonstrate the capabilities of modern language workbenches by modeling and implementing a relatively simple but representative DSL. For the 2025 edition, the language to implement is the **Questionnaire Language (QL)**.
The QL task asks participants to implement a small DSL for **questionnaires** featuring: questions grouped in forms; labels; types; optional computed values; **conditional visibility and grouping**; and an expression language for conditions and computations. A QL description should render to a GUI where enabled questions become visible and computed values update live. (The optional QLS layer adds layout/styling and widget choices.)

## Our implementation

### Metamodel — concepts

### Concrete syntax — projections

### Execution model & GUI generation

### Validation

### Styling & personalization

### Limitations


## Quick start

<!-- **Requirements:** Node.js ≥ 20; pnpm or npm. -->

# Pretoria BI — Public Portfolio Standard

This document defines the minimum evidence required before a repository is treated as strong public portfolio work.

## Core rule

> A repository does not receive credit for a claim because the claim appears in documentation. It receives credit when the claim is backed by inspectable evidence and a plausible failure path.

## Six proof layers

### 1. Business proof
- explicit decision problem;
- intended user or owner;
- action that could follow from the analysis;
- commercial language separated from technical evidence.

### 2. Data proof
- natural grain documented;
- business keys explicit;
- schema/domain controls;
- reconciliation where source and target states differ;
- synthetic/public-data boundary documented.

### 3. Analytical proof
- baseline before complexity;
- appropriate statistical or predictive method;
- leakage controls;
- out-of-sample or counterfactual validation where relevant;
- limitations stated next to results.

### 4. Engineering proof
- reproducible environment;
- deterministic execution where expected;
- automated tests;
- static checks;
- source-controlled configuration.

### 5. Operational proof
- CI;
- controlled corruption / reverse test;
- fail-closed behavior for material defects;
- deterministic recovery path;
- monitoring or persisted evidence when the use case requires it.

### 6. Value proof
- signal linked to a decision;
- action owner;
- follow-up metric;
- assumptions visible;
- modeled opportunity clearly distinguished from realised impact.

## Flagship gate

A project approaches flagship status only when:

1. the central business question is difficult enough to justify the architecture;
2. multiple proof layers are implemented, not merely described;
3. the repository contains at least one deliberate failure injection;
4. critical calculations reconcile independently;
5. predictive work beats a documented baseline before acceptance;
6. BI/semantic assets are source-controlled when BI is a core deliverable;
7. public claims stay within the evidence boundary;
8. remaining gaps are explicitly visible rather than hidden.

## Current live portfolio roles

- **Hospitality Intelligence Platform** — flagship decision-system architecture.
- **Banking DataOps Monitoring** — operational data integrity / DataOps evidence.
- **Speed Dating Behavioral Analytics** — statistics, leakage-aware modelling and explainability.
- **Jericho107 profile** — portfolio navigation and commercial framing.

## Anti-patterns rejected

- empty folders created for appearance;
- screenshots without reproducible source;
- dashboards without metric governance;
- ML without a baseline;
- p-values without effect-size interpretation;
- reconciliation against the same in-memory state;
- synthetic opportunity presented as realised ROI;
- unsupported claims of production readiness;
- README sophistication exceeding repository evidence.

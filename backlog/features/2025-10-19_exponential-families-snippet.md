---
id: "2025-10-19_exponential-families-snippet"
title: "Create exponential families snippet for Lecture 1"
status: "Ready"
priority: "High"
created: "2025-10-19"
last_updated: "2025-10-19"
owner: "Neil Lawrence"
dependencies: "None"
tags:
- backlog
- phase-1
- lecture-01
- snippet-creation
- prerequisites
---

# Task: Create exponential families snippet for Lecture 1

## Description

Create comprehensive snippet on exponential families covering natural parameters, sufficient statistics, log partition function, and connection to Fisher information. This is foundational material for the entire course.

**Target file:** `~/lawrennd/snippets/_physics/includes/exponential-families.md`

**Estimated effort:** 1-2 days

## Acceptance Criteria

- [ ] Clear definition with natural parameters $\boldsymbol{\theta}$
- [ ] Sufficient statistics $T(\mathbf{x})$ explained
- [ ] Log partition function $\mathcal{A}(\boldsymbol{\theta})$ as cumulant generator
- [ ] Derivation of $\nabla H = -G(\boldsymbol{\theta})\boldsymbol{\theta}$
- [ ] Gaussian example showing $G^{-1} = \Sigma$
- [ ] Categorical distribution example
- [ ] Notation aligned with TIG paper
- [ ] Slides and notes sections included
- [ ] Code examples for computing partition function

## Implementation Notes

**Reference material:**
- `~/lawrennd/snippets/_information-game/includes/information-theory-overview.md` (lines 38-76)
- `~/lawrennd/snippets/_information-game/includes/quantum-exponential-family.md`

**Approach:**
- Start with classical exponential family
- Show concrete examples first (Gaussian, categorical)
- Build up to general properties
- Connect to TIG paper notation
- Keep pedagogical - this is first real lecture content

**Integration:**
- Will be included in `_lamd/lecture01-foundations.md`
- Prerequisite for Lecture 2 (axioms) and Lecture 3 (relaxation)

## Related

- CIP: 0001 (Phase 1)
- Lecture: 01-foundations
- Depends on: None (foundational)
- Blocks: Fisher information snippet, Lecture 2 axioms

## Progress Updates

### 2025-10-19
Task created with Ready status. High priority for Phase 1.


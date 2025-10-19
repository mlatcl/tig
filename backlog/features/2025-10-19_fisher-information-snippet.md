---
id: "2025-10-19_fisher-information-snippet"
title: "Adapt Fisher information snippet for Lecture 1"
status: "Ready"
priority: "High"
created: "2025-10-19"
last_updated: "2025-10-19"
owner: "Neil Lawrence"
dependencies: "2025-10-19_exponential-families-snippet"
tags:
- backlog
- phase-1
- lecture-01
- snippet-adaptation
- prerequisites
---

# Task: Adapt Fisher information snippet for Lecture 1

## Description

Adapt existing Fisher information matrix snippet to focus on geometric interpretation for the first lecture. Need to simplify existing material, defer advanced topics (rcFIM, topography) to later lectures, and handle forward pointer from exponential families snippet.

**Target file:** `~/lawrennd/snippets/_information-game/includes/fisher-information-matrix.md`

**Estimated effort:** 1 day

## Acceptance Criteria

- [ ] Simplified from existing `fisher-information-matrix.md`
- [ ] Focus on standard FIM only (defer rcFIM to Lecture 9)
- [ ] Emphasize geometric interpretation (metric on parameter space)
- [ ] Handle backward reference from exponential families snippet
- [ ] Connect $G(\boldsymbol{\theta}) = \nabla^2 \mathcal{A}$ to covariance
- [ ] Explain Cramér-Rao bound (brief, building on exponential families mention)
- [ ] Show geometric intuition: distances, geodesics, information geometry
- [ ] Examples: Gaussian (Fisher information = $\Sigma$), categorical
- [ ] Notation aligned with TIG paper
- [ ] Slides and notes sections included

## Implementation Notes

**Reference material:**
- `~/lawrennd/snippets/_information-game/includes/fisher-information-matrix.md` (existing)
- `~/lawrennd/snippets/_information-game/includes/information-topography.md` (mine for basic geometric intuition)

**Approach:**
- Start by acknowledging forward pointer from exponential families
- Develop geometric picture: Fisher information as Riemannian metric
- Connection to Cramér-Rao: tighter bound = smaller "volume" in parameter space
- Keep pedagogical - geometric intuition over technical details
- Explicitly defer rcFIM and topography to Lectures 8-9

**Key concepts to cover:**
1. Fisher information as metric tensor on parameter space
2. Information distance between distributions
3. Geodesics in information space
4. Connection to statistical estimation (Cramér-Rao)
5. Why this matters for information dynamics

**Integration:**
- Will be included in `_lamd/lecture01-foundations.md` after exponential families
- Prerequisite for understanding information relaxation (Lecture 3)
- Foundation for understanding resolution constraints (Lecture 9)

## Related

- CIP: 0001 (Phase 1)
- Lecture: 01-foundations
- Depends on: 2025-10-19_exponential-families-snippet
- Blocks: Lecture 3 relaxation, Lecture 9 topography

## Progress Updates

### 2025-10-19
Task created with Ready status. High priority for Phase 1. Depends on exponential families snippet completion.

Forward pointer requirement identified:
- Exponential families snippet includes: "As we'll see in the next section, the Fisher information matrix also defines the geometry of the information space."
- This snippet must fulfill that promise by developing the geometric interpretation.



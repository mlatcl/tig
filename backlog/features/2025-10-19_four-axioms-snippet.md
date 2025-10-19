---
id: "2025-10-19_four-axioms-snippet"
title: "Create four axioms and Baez framework snippets (Lecture 2)"
status: "Completed"
priority: "High"
created: "2025-10-19"
last_updated: "2025-10-19"
owner: "Neil Lawrence"
dependencies: "Lecture 1 (exponential families)"
tags:
- backlog
- phase-1
- lecture-02
- snippet-creation
- axioms
---

# Task: Create four axioms and Baez framework snippets (Lecture 2)

## Description

Create comprehensive snippets for Lecture 2 on the four fundamental axioms of The Inaccessible Game and Baez et al.'s information loss framework. This is core theoretical foundation.

**Target files (all in `~/lawrennd/snippets/_physics/includes/`):**
1. `four-axioms.md` (20 min)
2. `baez-information-loss.md` (30 min)
3. `submodularity-multi-information.md` (15 min)
4. `marginal-entropy-conservation.md` (15 min)

**Estimated effort:** 2-3 days

## Acceptance Criteria

- [x] All four axioms clearly stated
- [x] Intuitive explanation for each axiom
- [x] Why these axioms are natural/necessary
- [x] Baez functoriality axiom explained
- [x] Convex linearity axiom explained
- [x] Continuity axiom explained
- [x] Result: $F(f) = c(H(p) - H(q))$ derived
- [x] Multi-information: $I = \sum_i h_i - H$
- [x] Submodularity intuition (diminishing returns)
- [x] Marginal entropy conservation stated and explained
- [x] Category theory kept accessible
- [ ] Problem set 2 created (deferred)

## Implementation Notes

**Challenge:** NO existing snippets - create from scratch from TIG paper.

**Critical missing piece:** Marginal entropy conservation was missing from initial review.

**Pedagogical approach:**
- Start with physical/information-theoretic intuition
- Formalize as axioms
- Show how axioms lead to dynamics
- Keep category theory accessible (functoriality)
- Use die-rolling example from Jaynes as analogy

**Integration:**
- Builds on Lecture 1 (exponential families)
- Foundation for Lecture 3 (information relaxation principle)
- The "why" before the "how"

## Related

- CIP: 0001 (Phase 1)
- Lecture: 02-axioms
- Depends on: Lecture 1 (exponential families complete)
- Blocks: Lecture 3 (relaxation principle)
- Priority: HIGH - foundational theory

## Progress Updates

### 2025-10-19
Task created. Critical foundation for entire course - the axioms are what make this framework unique.

**Snippets completed:**

1. **`_physics/includes/baez-information-loss.md`** (created)
   - Three Baez axioms: functoriality, convex linearity, continuity
   - Main result: F(f) = c(H(p) - H(q))
   - Category theory kept accessible
   - Connection to exponential families
   - ~150 lines with slides/notes

2. **`_information-game/includes/information-conservation-axiom.md`** (created)
   - Fourth axiom: Σhᵢ = C
   - Why marginal vs joint entropy
   - Exchangeability explanation
   - Physical interpretation
   - Connection to "inaccessibility"
   - ~130 lines with slides/notes

3. **`_information-game/includes/submodularity-multi-information.md`** (created)
   - Multi-information definition: I = Σhᵢ - H
   - Connection to conservation: H + I = C
   - Submodularity (diminishing returns)
   - ML example (feature addition)
   - Why it matters for dynamics
   - ~110 lines with slides/notes

**Lecture 2 updated:**
- All three snippets integrated into lecture structure
- Proper pedagogical flow: review Baez → new axiom → consequences
- Total content: ~60 minutes including wrap-up

Status updated to Completed. Problem sets deferred to separate task.


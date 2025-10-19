---
id: "2025-10-19_poisson-brackets-lecture"
title: "Create complete Poisson brackets lecture materials (Lecture 5)"
status: "Ready"
priority: "High"
created: "2025-10-19"
last_updated: "2025-10-19"
owner: "Neil Lawrence"
dependencies: "Lectures 1-4 complete"
tags:
- backlog
- phase-2
- lecture-05
- major-gap
- new-content
---

# Task: Create complete Poisson brackets lecture materials (Lecture 5)

## Description

Create comprehensive Poisson brackets lecture from scratch. This is identified in CIP-0001 as "the most important new concept" and a major gap in existing snippets (only 5% coverage).

**Target files (all in `~/lawrennd/snippets/_physics/includes/`):**
1. `why-energy-conserves.md` (10 min)
2. `poisson-brackets-definition.md` (15 min)
3. `hamiltonian-flow.md` (15 min)
4. `casimir-functions.md` (15 min)
5. `poisson-meets-fisher.md` (5 min)

**Estimated effort:** 2-3 days focused work

## Acceptance Criteria

- [ ] Motivation: Why energy conservation leads to antisymmetric structure
- [ ] Clear definition: $\{f,g\} = (\nabla f)^\top A (\nabla g)$
- [ ] Antisymmetry, bilinearity, Jacobi identity explained
- [ ] Hamiltonian flow: $\dot{q} = A \nabla H$
- [ ] Energy conservation proof from antisymmetry
- [ ] Casimir functions when $A$ is degenerate
- [ ] Symplectic leaves (intuitive, not full theory)
- [ ] Connection to information dynamics preview
- [ ] Worked examples (harmonic oscillator)
- [ ] Problem set 5 created
- [ ] Slide deck with geometric visualizations
- [ ] All notation consistent with course

## Implementation Notes

**Challenge:** NO existing snippets to draw from. Must create from first principles.

**Pedagogical approach:**
1. Start with motivation: "What if dynamics conserve energy?"
2. Show antisymmetric $A$ ensures $\frac{\text{d}E}{\text{d}t} = 0$
3. Formalize as Poisson bracket
4. Build up properties
5. Connect to Hamiltonian mechanics
6. Preview GENERIC (symmetric + antisymmetric)

**Resources:**
- Marsden & Ratiu textbook for rigorous treatment
- Keep accessible for graduate students without mechanics background
- Focus on information-theoretic applications

**Integration:**
- Critical for understanding GENERIC structure (Lecture 8)
- Needed for perturbation analysis decomposition (Lecture 7)

## Related

- CIP: 0001 (Phase 2)
- Lecture: 05-poisson-brackets
- Depends on: Lectures 1-4 (especially Lagrangian formulation)
- Blocks: Lecture 7 (symmetric/antisymmetric split), Lecture 8 (GENERIC)
- Priority: HIGH - identified as major gap and critical concept

## Progress Updates

### 2025-10-19
Task created with Ready status. This is one of three major new content areas (along with perturbation analysis and GENERIC).


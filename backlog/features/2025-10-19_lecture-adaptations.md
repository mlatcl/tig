---
id: "2025-10-19_lecture-adaptations"
title: "Adapt existing snippets for Lectures 1, 3, 4, 9"
status: "Ready"
priority: "Medium"
created: "2025-10-19"
last_updated: "2025-10-19"
owner: "Neil Lawrence"
dependencies: "None for L1, others depend on prerequisites"
tags:
- backlog
- adaptation
- multiple-lectures
- existing-content
---

# Task: Adapt existing snippets for Lectures 1, 3, 4, 9

## Description

Several lectures have existing snippet material that needs adaptation rather than creation from scratch. These need verification against current paper, notation alignment, and pedagogical restructuring.

**Lectures requiring adaptation:**
- Lecture 1: Fisher information, information theory overview
- Lecture 3: Gradient flow, entropy maximization
- Lecture 4: Lagrangian formulation, constraints
- Lecture 9: Information topography, regime emergence

**Estimated effort:** ~6-8 days total

## Acceptance Criteria

### Lecture 1 Adaptations
- [ ] Adapt `fisher-information-matrix.md` (simplify for intro, defer rcFIM)
- [ ] Adapt `quantum-exponential-family.md` (verify alignment, defer quantum)
- [ ] Rewrite `information-theory-overview.md` (ADD conservation constraint)

### Lecture 3 Adaptations  
- [ ] Rewrite `entropy-gradient-ascent.md` (ADD conservation, tie to axioms)
- [ ] Adapt `gradient-flow-least-action.md` (emphasize constraints)
- [ ] Position `jaynes-maximum-entropy.md` (context only)

### Lecture 4 Adaptations
- [ ] Verify `action-potential-formulation.md` (check paper alignment)
- [ ] Extract constraint material from `emergent-observables.md`
- [ ] Review Kirchhoff analogy notebook

### Lecture 9 Adaptations
- [ ] Adapt `information-topography.md` (verify paper alignment)
- [ ] Review `jaynes-world-information-reservoirs.md` (check relevance)
- [ ] Extract regime material from `emergent-observables.md`
- [ ] Review `spontaneous-organization.md` for ideas

## Implementation Notes

**Key challenge:** CONSERVATION CONSTRAINT MISSING from existing material.

Many existing snippets are from older formulations and don't include the conservation constraint that's central to the current paper. This must be added throughout.

**Approach:**
1. Read existing snippet
2. Verify against current TIG paper
3. Add conservation where missing
4. Align notation
5. Restructure for pedagogy
6. Test with sample problems

**Quality markers:**
- MODERATE to SIGNIFICANT rewrites needed
- Not just "light editing"
- Substantial alignment work required

## Related

- CIP: 0001 (Phases 1, 2, 3)
- Lectures: 01, 03, 04, 09
- Depends on: Access to current TIG paper
- Blocks: Respective lecture completion
- Priority: MEDIUM - important but less critical than new content creation

## Progress Updates

### 2025-10-19
Task created. Emphasized that these are not simple adaptations - conservation constraint must be added throughout, and older formulations may need significant rework.


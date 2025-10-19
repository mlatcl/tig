---
title: "Lecture 6: Perturbation Analysis I - Modified Laplace Expansion"
week: 3
session: 2
featured_image: slides/diagrams/tig-perturbation.svg
abstract: >
  Perturbation analysis around equilibrium points. Covers modified Laplace
  expansion, Taylor series to third order, and on-manifold reduction
  techniques. Most mathematically dense lecture in the course.
author:
- given: Neil
  family: Lawrence
  institution: University of Cambridge
  url: http://inverseprobability.com
venue: University of Cambridge
transition: None
---

\section{Lecture Overview}

\notes{**Duration:** 50 minutes

**Prerequisites:**
- Lectures 1-5
- Taylor series expansion (will review)

**Learning Objectives:**
1. Understand perturbation around equilibrium $\boldsymbol{\theta}^\ast$
2. Master modified Laplace expansion technique
3. Learn on-manifold reduction
4. Handle third-order terms in tensor notation
}

\notes{**WARNING:** Most mathematically dense lecture. Go slowly!}

\section{Required Snippets}

\subsection{Taylor Expansion Review (10 min)}

\notes{
**Snippet: `taylor-expansion-review.md`**
- **Status:** ❌ NEEDS CREATION
- **Location:** Create in `~/lawrennd/snippets/_maths/includes/`
- **Needs:**
  - Expanding $F(\boldsymbol{\theta}^\ast + q)$ to third order
  - Scalar function: $F(x+h) = F(x) + F'(x)h + \frac{1}{2}F''(x)h^2 + ...$
  - Vector function: Gradient, Hessian, third-order tensor
  - Tensor notation: $T[q,q]$ means $\sum_{jk} T_{ijk} q_j q_k$
  - Index notation vs matrix notation
- **Rewrite needed:** N/A - create from scratch
}

\subsection{Modified Laplace Expansion (20 min)}

\notes{
**Snippet: `modified-laplace-expansion.md`**
- **Status:** ⚠️ Possible implicit coverage
- **Source check:** `~/lawrennd/snippets/_information-game/includes/jaynesian-derivation-minimal-entropy.md`
- **Likely status:** SIGNIFICANT REWRITE NEEDED
- **Needs:**
  - Standard Laplace expansion review
  - Modification for constrained manifold
  - Handling constraint in expansion
  - Connection to equilibrium points
  - Why this differs from standard perturbation theory
- **Rewrite needed:** Likely full rewrite from TIG paper
}

\notes{
**Snippet: `latent-phase-constraints.md`**
- **Status:** ✅ EXISTS but unclear relevance
- **Location:** `~/lawrennd/snippets/_information-game/includes/latent-phase-constraints.md`
- **Usage:** May have perturbation ideas, needs review
- **Rewrite needed:** Review first, likely SIGNIFICANT
}

\subsection{On-Manifold Reduction (15 min)}

\notes{
**Snippet: `on-manifold-reduction.md`**
- **Status:** ❌ NEEDS CREATION
- **Source reference:** TIG paper perturbation section
- **Needs:**
  - Projection onto constraint manifold
  - Tangent space coordinates
  - Reduced dynamics on manifold
  - Connection to $\Pi_\parallel$ from Lecture 4
  - Why manifold geometry matters
- **Rewrite needed:** N/A - create from scratch
}

\subsection{Third-Order Terms (10 min)}

\notes{
**Snippet: `third-order-tensor-notation.md`**
- **Status:** ❌ NEEDS CREATION  
- **Location:** Create in `~/lawrennd/snippets/_maths/includes/`
- **Needs:**
  - Tensor contraction notation
  - Symmetry properties
  - Computational handling
  - When to keep vs neglect
- **Rewrite needed:** N/A - create from scratch
}

\section{Planned Structure}

\subsection{Review and Motivation (5 min)}

\notes{
- Equilibria from Lecture 4
- Why study perturbations?
- Local vs global dynamics
}

\subsection{Taylor Expansion Primer (10 min)}

\notes{
\include{_maths/includes/taylor-expansion-review.md}
\include{_maths/includes/third-order-tensor-notation.md}
}

\subsection{Modified Laplace Expansion (20 min)}

\notes{
\include{_physics/includes/modified-laplace-expansion.md}
}

\subsection{On-Manifold Reduction (15 min)}

\notes{
\include{_physics/includes/on-manifold-reduction.md}
}

\subsection{Summary and Preview (5 min)}

\notes{
- What we can now compute
- Preview: Symmetric/antisymmetric split (Lecture 7)
}

\section{Problems and Exercises}

\notes{
**Problem Set 6:** ⚠️ NEEDS CREATION
- Taylor expand simple functions to third order
- Practice tensor notation
- Compute modified Laplace expansion for 2D example
- Project dynamics onto manifold
**Note:** Keep problems concrete and computational
}

\section{Implementation Status}

\notes{
**HIGH PRIORITY - Mostly new content**
- [ ] Create taylor-expansion-review.md snippet
- [ ] Create third-order-tensor-notation.md snippet
- [ ] Review jaynesian-derivation and latent-phase-constraints snippets
- [ ] Create/rewrite modified-laplace-expansion.md snippet
- [ ] Create on-manifold-reduction.md snippet
- [ ] Create problem set 6 with worked examples
- [ ] Create slide deck with clear notation
- [ ] Develop step-by-step computational examples
- [ ] Test for clarity (this is the hard lecture!)
}

\notes{
**Estimated effort:** ~3-4 days
**Challenge:** Making dense mathematics accessible
}

\thanks

\references


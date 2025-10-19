---
title: "Lecture 7: Perturbation Analysis II - Symmetric/Antisymmetric Split"
week: 4
session: 1
featured_image: slides/diagrams/tig-split.svg
abstract: >
  Second-order dynamics and the symmetric/antisymmetric decomposition.
  Covers how conservative and dissipative parts emerge from the
  perturbation analysis, setting up GENERIC structure.
author:
- given: Neil
  family: Lawrence
  institution: University of Cambridge
  url: http://inverseprobability.com
date: 2025-10-19
venue: University of Cambridge
transition: None
---

\section{Lecture Overview}

\notes{**Duration:** 50 minutes

**Prerequisites:**
- Lecture 6 (perturbation techniques)
- Lecture 5 (Poisson brackets)

**Learning Objectives:**
1. Understand second-order dynamics near equilibrium
2. Master symmetric/antisymmetric decomposition
3. See how conservative vs dissipative parts emerge
4. Preview GENERIC structure (Lecture 8)
}

\section{Required Snippets}

\subsection{Matrix Decomposition Review (10 min)}

\notes{
**Snippet: `symmetric-antisymmetric-decomposition.md`**
- **Status:** ⚠️ May exist in _maths
- **Source check:** `~/lawrennd/snippets/_maths/includes/`
- **Needs:**
  - Any matrix: $M = S + A$ where $S^\top = S$, $A^\top = -A$
  - Unique decomposition: $S = \frac{1}{2}(M + M^\top)$, $A = \frac{1}{2}(M - M^\top)$
  - Physical interpretation
  - Properties of each part
- **Rewrite needed:** Check if exists, otherwise CREATE
}

\subsection{Second-Order Dynamics (20 min)}

\notes{
**Snippet: `second-order-information-dynamics.md`**
- **Status:** ❌ NEEDS CREATION
- **Source reference:** TIG paper perturbation results
- **Needs:**
  - Linearized dynamics: $\dot{q} = M q$ where $q = \boldsymbol{\theta} - \boldsymbol{\theta}^\ast$
  - Matrix $M$ from perturbation expansion
  - How $M$ encodes second-order behavior
  - Stability analysis preview
- **Rewrite needed:** N/A - create from scratch
}

\subsection{The Split and Its Meaning (20 min)}

\notes{
**Snippet: `conservative-dissipative-emergence.md`**
- **Status:** ❌ NEEDS CREATION
- **Source reference:** TIG paper key result
- **Needs:**
  - $M = S + A$ decomposition
  - $A$ part: Hamiltonian/conservative flow
  - $S$ part: Gradient/dissipative flow
  - Why this emerges from information geometry
  - Connection to Poisson brackets (Lecture 5)
  - Preview of GENERIC (Lecture 8)
- **Rewrite needed:** N/A - create from scratch
}

\notes{
**Potential reference:** `~/lawrennd/snippets/_information-game/includes/intelligence-thermodynamics-connection.md`
- **Status:** ✅ EXISTS, mentions GENERIC
- **Quality:** May have relevant ideas
- **Usage:** Mine for intuition, but likely needs rewrite
- **Rewrite needed:** Review and extract relevant parts
}

\subsection{Stability and Eigenvalues (Optional 10 min)}

\notes{
**Snippet: `stability-from-eigenvalues.md`**
- **Status:** ❌ NEEDS CREATION
- **Needs:**
  - Eigenvalue analysis of $M$
  - Stable, unstable, center manifolds
  - How symmetry affects eigenvalues
  - Physical interpretation
- **Rewrite needed:** N/A - create from scratch
}

\section{Planned Structure}

\subsection{Review (5 min)}

\notes{
- Perturbation expansion from Lecture 6
- Leading order dynamics
}

\subsection{Matrix Decomposition (10 min)}

\notes{
\include{_maths/includes/symmetric-antisymmetric-decomposition.md}
}

\subsection{Second-Order Dynamics (15 min)}

\notes{
\include{_physics/includes/second-order-information-dynamics.md}
}

\subsection{Conservative vs Dissipative (15 min)}

\notes{
\include{_physics/includes/conservative-dissipative-emergence.md}
}

\subsection{Stability Analysis (Optional 10 min)}

\notes{
\include{_maths/includes/stability-from-eigenvalues.md}
}

\subsection{Preview GENERIC (5 min)}

\notes{
- This split is fundamental
- Next lecture: Full GENERIC structure
}

\section{Problems and Exercises}

\notes{
**Problem Set 7:** ⚠️ NEEDS CREATION
- Decompose matrices into symmetric/antisymmetric parts
- Compute second-order dynamics for examples
- Analyze stability from eigenvalues
- Identify conservative vs dissipative components
- Connect to physical examples (harmonic oscillator with damping)
}

\section{Implementation Status}

\notes{
**MEDIUM-HIGH PRIORITY**
- [ ] Check for symmetric-antisymmetric-decomposition.md or create
- [ ] Create second-order-information-dynamics.md snippet
- [ ] Create conservative-dissipative-emergence.md snippet
- [ ] Review intelligence-thermodynamics-connection.md for ideas
- [ ] Create stability-from-eigenvalues.md snippet (optional)
- [ ] Create problem set 7
- [ ] Create slide deck emphasizing the split
- [ ] Develop physical intuition examples
}

\notes{
**Estimated effort:** ~2-3 days
**Key challenge:** Connecting abstract decomposition to physical meaning
}

\thanks

\references


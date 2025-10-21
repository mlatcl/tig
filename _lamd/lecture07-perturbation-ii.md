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
- **Status:** ✅ CREATED (2025-10-21)
- **Location:** `~/lawrennd/snippets/_maths/includes/symmetric-antisymmetric-decomposition.md`
- **Content:**
  - Unique decomposition: $M = S + A$
  - Formulas: $S = \frac{1}{2}(M + M^\top)$, $A = \frac{1}{2}(M - M^\top)$
  - Physical interpretation (dissipative vs conservative)
  - Frobenius orthogonality
  - 2D worked example
}

\subsection{Second-Order Dynamics (20 min)}

\notes{
**Snippet: `second-order-information-dynamics.md`**
- **Status:** ✅ CREATED (2025-10-21)
- **Location:** `~/lawrennd/snippets/_physics/includes/second-order-information-dynamics.md`
- **Content:**
  - Perturbation expansion: $F = \Pi_\parallel S q + \mathcal{B}(q) + O(\|q\|^3)$
  - Leading order is purely symmetric (dissipative)
  - Entropy production: $\dot{H} \approx -q^\top S q$
  - Connection to Gaussian/Laplace regime
  - Stability from eigenvalues of $\Pi_\parallel S \Pi_\parallel$
}

\subsection{The Split and Its Meaning (20 min)}

\notes{
**Snippet: `conservative-dissipative-emergence.md`**
- **Status:** ✅ CREATED (2025-10-21)
- **Location:** `~/lawrennd/snippets/_physics/includes/conservative-dissipative-emergence.md`
- **Content:**
  - Third-order corrections: $\mathcal{B}(q)$ from cumulants and curvature
  - Jacobian creates antisymmetric component
  - GENERIC decomposition: $\nabla F = \Pi_\parallel S \Pi_\parallel + A$
  - Physical meaning: thermodynamics + mechanics
  - Connection to Poisson brackets
  - Why this emerges (not imposed)
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
**STATUS:** Core content complete!
- [x] Create symmetric-antisymmetric-decomposition.md snippet (COMPLETED 2025-10-21)
- [x] Create second-order-information-dynamics.md snippet (COMPLETED 2025-10-21)
- [x] Create conservative-dissipative-emergence.md snippet (COMPLETED 2025-10-21)
- [x] Core lecture content complete (~45 min material)
- [ ] Review intelligence-thermodynamics-connection.md for additional ideas
- [ ] Create stability-from-eigenvalues.md snippet (optional, for deeper dive)
- [ ] Create problem set 7
- [ ] Create slide deck

**Key achievement:** Successfully explained how GENERIC structure emerges from information geometry, connecting second-order (Gaussian/dissipative) to third-order (non-Gaussian/conservative) dynamics.
}

\thanks

\references


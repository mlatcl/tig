---
title: "Lecture 5: Poisson Brackets and Hamiltonian Structure"
week: 3
session: 1
featured_image: slides/diagrams/tig-poisson.svg
abstract: >
  Introduction to Poisson brackets from first principles. Covers
  antisymmetric structure, Hamiltonian flow, Casimir functions,
  and why energy conservation emerges from geometry.
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
- Lectures 1-4
- Lagrangian mechanics from Lecture 4

**Learning Objectives:**
1. Understand Poisson brackets from first principles
2. Grasp antisymmetric structure and its consequences
3. Learn about Hamiltonian flow and energy conservation
4. Understand Casimir functions and degeneracy
5. Connect to information dynamics
}

\section{Required Snippets}

\subsection{Motivation: Energy Conservation (10 min)}

\notes{
**Snippet: `why-energy-conserves.md`**
- **Status:** ✅ COMPLETED
- **Location:** `~/lawrennd/snippets/_physics/includes/`
- **Includes:**
  - Question: What if dynamics conserve energy?
  - Antisymmetric $A$ ensures $\frac{\text{d}E}{\text{d}t} = 0$
  - Pendulum animation example with matplotlib code
  - Accessible introduction for computer scientists
}

\subsection{Poisson Brackets Definition (15 min)}

\notes{
**Snippet: `poisson-brackets-definition.md`**
- **Status:** ✅ COMPLETED
- **Location:** `~/lawrennd/snippets/_physics/includes/`
- **Includes:**
  - Definition: $\{f,g\} = (\nabla f)^\top A (\nabla g)$
  - All properties: antisymmetry, bilinearity, Jacobi identity
  - Lie algebra intuition with 2D rotation visualization
  - Matrix exponential explained for non-physicists
  - Canonical Poisson bracket with connection to natural parameters
}

\subsection{Hamiltonian Flow (15 min)}

\notes{
**Snippet: `hamiltonian-flow.md`**
- **Status:** ✅ COMPLETED
- **Location:** `~/lawrennd/snippets/_physics/includes/`
- **Includes:**
  - Hamiltonian vector field: $\dot{q} = A \nabla H$
  - Hamilton's equations from Poisson bracket
  - Energy conservation proof
  - Phase space geometry with harmonic oscillator visualization
  - Beautiful circular orbits showing energy surfaces
}

\subsection{Casimir Functions (15 min)}

\notes{
**Snippet: `casimir-functions.md`**
- **Status:** ✅ COMPLETED
- **Location:** `~/lawrennd/snippets/_physics/includes/`
- **Includes:**
  - Casimirs as "super-conserved" quantities
  - When $A$ is degenerate: $\{C, f\} = 0$ for all $f$
  - Noether's theorem introduction (Emmy Noether, 1918)
  - Angular momentum example showing $|\mathbf{L}|^2$ as Casimir
  - Connection to TIG: $\sum h_i$ as information Casimir
}

\subsection{Connection to Information Dynamics (Optional 10 min)}

\notes{
**Snippet: `poisson-meets-fisher.md`**
- **Status:** ✅ COMPLETED
- **Location:** `~/lawrennd/snippets/_physics/includes/`
- **Includes:**
  - Preview of GENERIC (Grmela & Öttinger) from non-equilibrium thermodynamics
  - Poisson (reversible) + Fisher (irreversible) structure
  - Degeneracy conditions for consistency
  - Teaser for Lecture 8
}

\section{Planned Structure}

\subsection{Introduction (5 min)}

\notes{
- Recap: Fisher information and entropy dynamics
- Today: The other side—energy conservation
- Why Hamiltonian structure matters for information
}

\subsection{Motivation: Energy Conservation (10 min)}

\notes{
\include{_physics/includes/why-energy-conserves.md}
}

\subsection{Poisson Brackets Definition (15 min)}

\notes{
\include{_physics/includes/poisson-brackets-definition.md}
}

\subsection{Hamiltonian Flow (15 min)}

\notes{
\include{_physics/includes/hamiltonian-flow.md}
}

\subsection{Casimirs and Degeneracy (15 min)}

\notes{
\include{_physics/includes/casimir-functions.md}
}

\subsection{Preview: Information Dynamics (5 min)}

\notes{
\include{_physics/includes/poisson-meets-fisher.md}
}

\subsection{Wrap-up (5 min)}

\notes{
- Poisson structure summary
- Preview: Perturbation analysis
}

\section{Problems and Exercises}

\notes{
**Problem Set 5:** ⚠️ NEEDS CREATION
- Verify Poisson bracket properties
- Compute Hamiltonian flows
- Find Casimir functions for degenerate systems
- Prove energy conservation for specific Hamiltonians
- Connect to symplectic structure (advanced)
}

\section{Implementation Status}

\notes{
**HIGH PRIORITY - All new content**
- [x] Create why-energy-conserves.md snippet (COMPLETED - ~205 lines)
- [x] Create poisson-brackets-definition.md snippet (COMPLETED - ~200 lines)
- [x] Create hamiltonian-flow.md snippet (COMPLETED - ~240 lines)
- [x] Create casimir-functions.md snippet (COMPLETED - ~230 lines)
- [x] Create poisson-meets-fisher.md snippet (COMPLETED - ~185 lines)
- [ ] Create problem set 5
- [ ] Create slide deck with clear visualizations
- [ ] Test lecture flow

**Core lecture content complete:** All five Poisson brackets snippets created from scratch (~1060 lines total). Ready for integration into Lecture 5.
}

\thanks

\references


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
- **Status:** ❌ NEEDS CREATION
- **Location:** Create in `~/lawrennd/snippets/_physics/includes/`
- **Needs:**
  - Question: What if dynamics conserve energy?
  - Antisymmetric $A$ ensures $\frac{\text{d}E}{\text{d}t} = 0$
  - Show: $\frac{\text{d}E}{\text{d}t} = (\nabla E)^\top A (\nabla E) = 0$
  - Motivation for Poisson structure
- **Rewrite needed:** N/A - create from scratch
- **CRITICAL:** This is identified as most important new concept in CIP
}

\subsection{Poisson Brackets Definition (15 min)}

\notes{
**Snippet: `poisson-brackets-definition.md`**
- **Status:** ❌ NEEDS CREATION
- **Location:** Create in `~/lawrennd/snippets/_physics/includes/`
- **Needs:**
  - Definition: $\{f,g\} = (\nabla f)^\top A (\nabla g)$
  - Antisymmetry: $A^\top = -A$
  - Bilinearity
  - Jacobi identity (statement, not full proof)
  - Examples: canonical Poisson bracket
- **Rewrite needed:** N/A - create from scratch
}

\subsection{Hamiltonian Flow (15 min)}

\notes{
**Snippet: `hamiltonian-flow.md`**
- **Status:** ❌ NEEDS CREATION
- **Location:** Create in `~/lawrennd/snippets/_physics/includes/`
- **Needs:**
  - Hamiltonian vector field: $\dot{q} = A \nabla H$
  - Hamilton's equations from Poisson bracket
  - Energy conservation proof
  - Phase space geometry
  - Simple examples (harmonic oscillator)
- **Rewrite needed:** N/A - create from scratch
}

\subsection{Casimir Functions (15 min)}

\notes{
**Snippet: `casimir-functions.md`**
- **Status:** ❌ NEEDS CREATION
- **Location:** Create in `~/lawrennd/snippets/_physics/includes/`
- **Needs:**
  - When $A$ is degenerate (not full rank)
  - Casimirs: $\{C, f\} = 0$ for all $f$
  - Kernel of $A$ defines Casimirs
  - Symplectic leaves (intuition, not full theory)
  - Why degeneracy matters for information dynamics
- **Rewrite needed:** N/A - create from scratch
}

\subsection{Connection to Information Dynamics (Optional 10 min)}

\notes{
**Snippet: `poisson-meets-fisher.md`**
- **Status:** ❌ NEEDS CREATION
- **Needs:**
  - Preview of GENERIC structure
  - Hamiltonian part vs dissipative part
  - Why information dynamics has both
  - Teaser for Lecture 8
- **Rewrite needed:** N/A - create from scratch
}

\section{Planned Structure}

\subsection{Motivation (10 min)}

\notes{
- Why do we need Hamiltonian structure?
- Energy conservation from geometry
\include{_physics/includes/why-energy-conserves.md}
}

\subsection{Poisson Brackets (15 min)}

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
- [ ] Create why-energy-conserves.md snippet
- [ ] Create poisson-brackets-definition.md snippet
- [ ] Create hamiltonian-flow.md snippet
- [ ] Create casimir-functions.md snippet
- [ ] Create poisson-meets-fisher.md snippet
- [ ] Create problem set 5
- [ ] Create slide deck with clear visualizations
- [ ] Develop geometric intuition examples
- [ ] Test with sample audience for clarity
}

\notes{
**Note:** This lecture has NO existing snippets to draw from. 
Estimate ~2-3 days of focused work to create all materials.
}

\thanks

\references


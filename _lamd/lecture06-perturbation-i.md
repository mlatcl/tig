---
title: "Lecture 6: Perturbation Analysis - Linearisation Around Equilibrium"
week: 3
session: 2
featured_image: slides/diagrams/tig-perturbation.svg
abstract: >
  Standard perturbation analysis around equilibrium points in the Gaussian regime.
  Covers linearization of constrained dynamics, computing the linearization matrix M,
  and geometric interpretation. Builds foundation for symmetric/antisymmetric split.
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
- Lectures 1-5 (especially L4 on constrained dynamics)
- Basic Taylor series (will review briefly)

**Learning Objectives:**
1. Understand why Gaussian regime is natural (callback to L4)
2. Master standard linearization: $\dot{q} = Mq$
3. Compute linearization matrix $M$ explicitly
4. Interpret geometric meaning of $M$ components
5. See connection to Laplace approximation (sidebar)
}


\section{Required Snippets}

\subsection{Why Gaussian Regime? (10 min)}

\notes{
**Snippet: `gaussian-regime-motivation.md`**
- **Status:** ✅ CREATED (2025-10-20)
- **Location:** `~/lawrennd/snippets/_physics/includes/gaussian-regime-motivation.md`
- **Content:**
  - Callback to L4: Computing $\nabla h_i$ is exponentially hard
  - Gaussian regime: Closed-form marginal entropies
  - Physical motivation: Maximum entropy distributions
  - Laplace approximation: Why perturbation analysis works
  - **Key point:** Laplace is conceptual foundation, not main technique
}

\subsection{Standard Linearisation (25 min)}

\notes{
**Snippet: `linearisation-around-equilibrium.md`**
- **Status:** ✅ CREATED (2025-10-20)
- **Location:** `~/lawrennd/snippets/_physics/includes/linearisation-around-equilibrium.md`
- **Content:**
  - Perturb: $\boldsymbol{\theta} = \boldsymbol{\theta}^\ast + q$
  - Linearise constrained dynamics to first order
  - Compute linearisation matrix: $M = -G - \nu^\ast A + \frac{aa^\top G}{\|a\|^2}$
  - Geometric interpretation of three terms
  - Result: $\dot{q} = Mq$ (standard linear system)
}

\subsection{Worked Example (15 min)}

\notes{
**Snippet: `perturbation-2d-example.md`**
- **Status:** ✅ CREATED (2025-10-20)
- **Location:** `~/lawrennd/snippets/_physics/includes/perturbation-2d-example.md`
- **Content:**
  - Two binary variables (discrete, fully computable example)
  - Finding equilibria (independence at maximum entropy)
  - Computing Fisher information matrix explicitly
  - What $M$ matrix tells us (structure and interpretation)
  - Physical intuition: Tension between entropy and conservation
}

\section{Planned Structure}

\subsection{Review and Motivation (5 min)}

\notes{
- Equilibria from Lecture 4: $G\boldsymbol{\theta} + \nu a = 0$
- Challenge: Computing $\nu(t)$ in general is exponentially hard
- Why Gaussian regime is special (computationally and physically)
}

\section{Why Gaussian Regime? (10 min)}

\include{_physics/includes/gaussian-regime-motivation.md}

\section{Standard Linearisation (25 min)}

\include{_physics/includes/linearisation-around-equilibrium.md}

\section{Worked Example (12 min)}

\include{_physics/includes/perturbation-2d-example.md}

\section{Wrap-up and Preview (3 min)}

\notes{
- We have linearised dynamics: $\dot{q} = Mq$
- Matrix $M$ includes entropy gradient, constraint curvature, projection
- **Next lecture:** Decompose $M = S + A$
  - Antisymmetric part: Conservative flow
  - Symmetric part: Dissipative flow
  - This emerges naturally from the geometry!
}

\section{Problems and Exercises}

\notes{
**Problem Set 6:** ⚠️ NEEDS CREATION
- Verify marginal entropy formulas for binary variables
- Compute Fisher information matrix for 2D binary system
- Compute constraint gradient $a$ for the example
- Find equilibria for simple examples
- Compute linearisation matrix $M$ explicitly
- Analyze eigenvalues and stability
- Relate to Laplace approximation
**Note:** Focus on explicit, computable examples (both discrete and Gaussian)
}

\section{Implementation Status}

\notes{
- [x] Create gaussian-regime-motivation.md snippet (COMPLETED 2025-10-20)
- [x] Create linearisation-around-equilibrium.md snippet (COMPLETED 2025-10-20)
- [x] Create perturbation-2d-example.md snippet (COMPLETED 2025-10-20)
- [x] Core lecture content complete (~50 min material)
- [ ] Create problem set 6 with worked examples
- [ ] Create slide deck

**Simplified approach:** Standard perturbation analysis instead of "modified Laplace expansion"
- Cleaner story: Gaussian regime → linearisation → matrix M
- Laplace approximation as conceptual sidebar, not center stage
- Connects naturally to L4 (computational challenge) and L7 (M = S + A split)
}

\notes{
**Status:** Core content complete (~2 days actual vs 3-4 days estimated)
**Key decision:** Simplified from original plan—much cleaner!
}

\thanks

\references


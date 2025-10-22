---
title: "Foundations and Exponential Families"
week: 1
session: 1
featured_image: slides/diagrams/tig-foundations.svg
abstract: >
  Introduction to the mathematical foundations of The Inaccessible Game.
  Covers exponential families, Fisher information matrix, and basic
  information theory concepts essential for the course.
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
- Probability theory (graduate level)
- Linear algebra
- Basic optimization

**Learning Objectives:**
1. Understand exponential family distributions and their properties
2. Grasp the Fisher Information Matrix as a geometric object
3. Connect information theory to statistical mechanics
}

\section{Required Snippets}

\subsection{Exponential Families (30-40 min)}

\notes{
**Snippet: `exponential-families.md`**
- **Status:** ⚠️ NEEDS CREATION (some reference in `information-theory-overview.md`)
- **Source reference:** `~/lawrennd/snippets/_information-game/includes/information-theory-overview.md` (lines 38-76)
- **Needs:** 
  - Clear definition with natural parameters $\boldsymbol{\theta}$
  - Sufficient statistics $T(\mathbf{x})$
  - Log partition function $\mathcal{A}(\boldsymbol{\theta})$ as cumulant generator
  - Why $\nabla H = -G(\boldsymbol{\theta})\boldsymbol{\theta}$ has clean form
  - Examples: Gaussian (to show $G^{-1} = \Sigma$), categorical
- **Rewrite needed:** YES - align with TIG paper notation
}

\notes{
**Snippet: `quantum-exponential-family.md`**
- **Status:** ✅ EXISTS with rewrite needed
- **Location:** `~/lawrennd/snippets/_information-game/includes/quantum-exponential-family.md`
- **Quality:** Good pedagogical structure with slides/notes
- **Needs:** 
  - Verify alignment with paper's treatment
  - May defer quantum aspects to later lectures
  - Check notation consistency
- **Rewrite needed:** MODERATE - mostly alignment and notation
}

\subsection{Fisher Information as Geometry (20-30 min)}

\notes{
**Snippet: `fisher-information-matrix.md`**
- **Status:** ✅ EXISTS with rewrite needed
- **Location:** `~/lawrennd/snippets/_information-game/includes/fisher-information-matrix.md`
- **Quality:** Good coverage of FIM basics and rcFIM
- **Needs:**
  - Focus on standard FIM first
  - Save rcFIM for later lecture on resolution
  - Emphasize geometric interpretation
  - Connect $G(\boldsymbol{\theta}) = \nabla^2 \mathcal{A}$ to covariance
- **Rewrite needed:** MODERATE - simplify for first lecture, defer advanced topics
}

\notes{
**Snippet: `information-topography.md`**
- **Status:** ✅ EXISTS but for advanced topics
- **Location:** `~/lawrennd/snippets/_information-game/includes/information-topography.md`
- **Quality:** Advanced material
- **Usage:** Mine for geometric intuition about FIM, but save partitioning for Lecture 9
- **Rewrite needed:** Extract relevant concepts only
}

\subsection{Information Theory Basics (15-20 min)}

\notes{
**Snippet: `information-theory-overview.md`**
- **Status:** ✅ EXISTS with rewrite needed
- **Location:** `~/lawrennd/snippets/_physics/includes/information-theory-overview.md`
- **Quality:** Good historical context
- **Needs:**
  - Shannon entropy definition
  - Connection to thermodynamic entropy
  - Free energy and Legendre transform
  - **CRITICAL MISSING:** Conservation constraint for TIG
- **Rewrite needed:** SIGNIFICANT - add conservation, align with paper
}

\notes{
**Snippet: `jaynes-maximum-entropy.md`**
- **Status:** ✅ EXISTS, good quality
- **Location:** `~/lawrennd/snippets/_physics/includes/jaynes-maximum-entropy.md`
- **Quality:** Excellent pedagogical example (die rolling)
- **Needs:** 
  - Lagrange multiplier derivation
  - Connection to exponential families
  - May be more relevant for Lecture 3
- **Rewrite needed:** MINOR - mostly context/positioning
}

\section{Planned Structure}

\subsection{Introduction (5 min)}

\notes{
- Course overview and motivation
- The Inaccessible Game: What is it?
- Why information geometry?
}

\subsection{Exponential Families (30 min)}

\notes{
\include{_physics/includes/exponential-families.md}
\include{_information-game/includes/quantum-exponential-family.md}
}

\subsection{Fisher Information as Geometry (20 min)}

\notes{
\include{_information-game/includes/fisher-information-geometry.md}
}

\subsection{Wrap-up (5 min)}

\notes{
- Summary of key concepts
- Preview of next lecture
- Problem set 1 assigned
}

\section{Problems and Exercises}

\notes{
**Problem Set 1:** ⚠️ NEEDS CREATION
- Compute FIM for simple exponential families
- Verify cumulant generating function properties
- Geometric interpretation exercises
}

\section{Implementation Status}

\notes{
- [x] Create exponential-families.md snippet (COMPLETED)
- [x] Create fisher-information-geometry.md for intro (COMPLETED)
- [ ] Rewrite information-theory-overview.md with conservation (if needed)
- [ ] Create problem set 1
- [ ] Create slide deck
- [ ] Test code examples

**Core lecture content complete:** Exponential families and Fisher information geometry snippets are ready and integrated.
}

\thanks

\references


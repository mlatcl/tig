---
title: "Lecture 3: Information Relaxation Principle"
week: 2
session: 1
featured_image: slides/diagrams/tig-relaxation.svg
abstract: >
  The Information Relaxation Principle and the I + H = C structure.
  Covers the reverse Noether argument and why Maximum Entropy Principle
  emerges naturally from information dynamics.
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
- Lectures 1-2
- Understanding of entropy and axioms

**Learning Objectives:**
1. Understand the $I + H = C$ structure
2. Grasp the information relaxation principle
3. See how MEP emerges from second law + conservation
4. Derive the gradient flow dynamics $\dot{\boldsymbol{\theta}} = -G\boldsymbol{\theta}$
}

\section{Required Snippets}

\subsection{I + H = C Structure (20 min)}

\notes{
**Snippet: `i-plus-h-equals-c.md`**
- **Status:** ✅ CREATED
- **Location:** `~/lawrennd/snippets/_physics/includes/i-plus-h-equals-c.md`
- **Content:**
  - Multi-information $I$ definition
  - Joint entropy $H$ definition
  - Information action principle $I + H = C$
  - Physical analogy to classical mechanics
  - Information relaxation principle
  - Connection to marginal entropy conservation
}

\subsection{Information Relaxation to MEP (20 min)}

\notes{
**Snippet: `information-relaxation-mep.md`**
- **Status:** ✅ CREATED
- **Location:** `~/lawrennd/snippets/_physics/includes/information-relaxation-mep.md`
- **Content:**
  - Second law implies $\dot{H} \geq 0$, therefore $\dot{I} \leq 0$
  - Maximum entropy production principle
  - Derivation of $\dot{\boldsymbol{\theta}} = -G(\boldsymbol{\theta})\boldsymbol{\theta}$
  - Why this is the unique dynamics
  - Physical intuition and gas diffusion analogy
  - Preview of constrained dynamics
}

\notes{
**Note:** The two core snippets (i-plus-h-equals-c.md and information-relaxation-mep.md) provide complete coverage of Lecture 3 content, including:
- Conceptual framework for I + H = C
- Visualization of binary variable relaxation
- Derivation of MEP dynamics
- Physical intuition and examples
}

\section{Planned Structure}

\subsection{Review (5 min)}

\notes{
- Four axioms recap
- Conservation: $\sum h_i = C$
- Today's question: What dynamics does this imply?
}

\section{The I + H = C Structure (20 min)}

\include{_physics/includes/i-plus-h-equals-c.md}


\section{Information Relaxation to MEP (20 min)}


\include{_physics/includes/information-relaxation-mep.md}

\section{Wrap-up (5 min)}

\notes{
- Information relaxation as fundamental principle
- MEP gives unique dynamics: $\dot{\boldsymbol{\theta}} = -G\boldsymbol{\theta}$
- Preview: Adding Lagrangian constraints (Lecture 4)
}

\section{Problems and Exercises}

\notes{
**Problem Set 3:** ⚠️ NEEDS CREATION
- Verify $I + H = C$ for simple systems
- Compute constrained gradient flows
- Simulate entropy maximization with conservation
- Connect to least action principles
}

\section{Implementation Status}

\notes{
- [x] Create i-plus-h-equals-c.md snippet (COMPLETED)
- [x] Create information-relaxation-mep.md snippet (COMPLETED)
- [x] Core lecture content complete (~45 min of material)
- [ ] Create problem set 3
- [ ] Create slide deck
- [ ] Test/run visualisation code (binary relaxation example)

**Note**: Removed quantum-specific gradient flow snippets (entropy-gradient-ascent, gradient-flow-least-action) as they don't fit TIG context. The i-plus-h-equals-c snippet already includes a suitable visualization of information relaxation.
}

\thanks

\references


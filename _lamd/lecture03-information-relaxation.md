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

\subsection{Emergence of MEP (15 min)}

\notes{
**Snippet: `entropy-gradient-ascent.md`**
- **Status:** ✅ EXISTS with significant rewrite needed
- **Location:** `~/lawrennd/snippets/_information-game/includes/entropy-gradient-ascent.md`
- **Quality:** Has entropy maximization content
- **Needs:**
  - Focus on why entropy increases
  - **CRITICAL MISSING:** Add conservation constraint
  - Connect to $I + H = C$
  - Gradient ascent as consequence not assumption
- **Rewrite needed:** SIGNIFICANT - add conservation, tie to axioms
}

\notes{
**Snippet: `jaynes-maximum-entropy.md`**
- **Status:** ✅ EXISTS, needs assimilation
- **Location:** `~/lawrennd/snippets/_physics/includes/jaynes-maximum-entropy.md`
- **Quality:** Excellent historical context
- **Usage:** Show how TIG generalizes Jaynes's principle
- **Rewrite needed:** MINOR - context/positioning only
}

\subsection{Gradient Flow (15 min)}

\notes{
**Snippet: `gradient-flow-least-action.md`**
- **Status:** ✅ EXISTS with rewrite needed
- **Location:** `~/lawrennd/snippets/_information-game/includes/gradient-flow-least-action.md`
- **Quality:** Good visualization and code
- **Needs:**
  - Emphasize constrained gradient flow
  - Add conservation constraint to dynamics
  - Connect to information-theoretic action
- **Rewrite needed:** MODERATE - add conservation emphasis
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


\section{Gradient Flow Implementation (15 min)}

\include{_information-game/includes/entropy-gradient-ascent.md}
}

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
- [ ] Rewrite entropy-gradient-ascent.md with conservation (NEEDS WORK)
- [ ] Adapt gradient-flow-least-action.md for TIG context (NEEDS WORK)
- [ ] Position jaynes-maximum-entropy.md for context (OPTIONAL)
- [ ] Create problem set 3
- [ ] Create slide deck
- [ ] Test code examples with conservation constraint
}

\thanks

\references


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
2. Grasp the reverse Noether argument
3. See how MEP emerges from information dynamics
4. Connect to gradient flow and entropy maximization
}

\section{Required Snippets}

\subsection{I + H = C Structure (20 min)}

\notes{
**Snippet: `i-plus-h-equals-c.md`**
- **Status:** ❌ NEEDS CREATION
- **Source reference:** TIG paper core result
- **Needs:**
  - Multi-information $I$ definition
  - Joint entropy $H$ definition
  - Constant $C$ and conservation
  - Why this structure is fundamental
  - Connection to marginal entropy conservation
- **Rewrite needed:** N/A - create from scratch
}

\subsection{Reverse Noether Argument (20 min)}

\notes{
**Snippet: `reverse-noether.md`**
- **Status:** ❌ NEEDS CREATION
- **Source reference:** TIG paper
- **Needs:**
  - Standard Noether's theorem review (symmetry → conservation)
  - Reverse direction (conservation → dynamics)
  - How $I + H = C$ implies specific dynamics
  - Connection to Lagrangian formulation
- **Rewrite needed:** N/A - create from scratch
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
- Axioms and conservation
- Setting up the dynamics question
}

\subsection{The I + H = C Structure (20 min)}

\notes{
\include{_physics/includes/i-plus-h-equals-c.md}
}

\subsection{Reverse Noether Argument (15 min)}

\notes{
\include{_physics/includes/reverse-noether.md}
}

\subsection{Gradient Flow and MEP (15 min)}

\notes{
\include{_information-game/includes/entropy-gradient-ascent.md}
\include{_information-game/includes/gradient-flow-least-action.md}
}

\subsection{Wrap-up (5 min)}

\notes{
- Why these dynamics are unique
- Preview: Adding Lagrangian constraints
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
- [ ] Create i-plus-h-equals-c.md snippet
- [ ] Create reverse-noether.md snippet
- [ ] Rewrite entropy-gradient-ascent.md with conservation
- [ ] Adapt gradient-flow-least-action.md
- [ ] Position jaynes-maximum-entropy.md for context
- [ ] Create problem set 3
- [ ] Create slide deck
- [ ] Create visualization of constrained gradient flow
}

\thanks

\references


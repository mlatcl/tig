---
title: "The Four Axioms and Information Loss"
week: 1
session: 2
featured_image: slides/diagrams/tig-axioms.svg
abstract: >
  The four fundamental axioms of The Inaccessible Game framework.
  Covers Baez et al.'s information loss axioms, submodularity,
  and marginal entropy conservation.
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
- Lecture 1 content
- Category theory basics (functors) - will be explained

**Learning Objectives:**
1. Understand the four axioms of information dynamics
2. Grasp Baez et al.'s information loss framework
3. Understand submodularity and its implications
4. See why marginal entropy conservation is natural
}

\section{Required Snippets}

\subsection{The Four Axioms (20 min)}

\notes{
**Snippet: `four-axioms.md`**
- **Status:** ❌ NEEDS CREATION
- **Source reference:** TIG paper section on axioms
- **Needs:** 
  - Clear statement of all four axioms
  - Intuitive explanation for each
  - Why these axioms are natural/necessary
  - Relationship between axioms
- **Rewrite needed:** N/A - create from scratch
}

\subsection{Baez Information Loss (30 min)}

\notes{
**Snippet: `baez-information-loss.md`**
- **Status:** ❌ NEEDS CREATION
- **Source reference:** Baez et al. papers + TIG paper
- **Needs:**
  - Functoriality axiom
  - Convex linearity axiom
  - Continuity axiom
  - Result: $F(f) = c(H(p) - H(q))$
  - Why this justifies using entropy differences
  - Connection to category theory (keep accessible)
- **Rewrite needed:** N/A - create from scratch
}

\subsection{Submodularity (15 min)}

\notes{
**Snippet: `submodularity-multi-information.md`**
- **Status:** ⚠️ NEEDS CREATION (some references exist)
- **Source reference:** Search snippets for multi-information
- **Potential sources:**
  - `~/lawrennd/snippets/_information-game/includes/conditional-independence-structures.md`
  - `~/lawrennd/snippets/_information-game/includes/intelligence-thermodynamics-connection.md`
- **Needs:**
  - Multi-information definition: $I = \sum_i h_i - H$
  - Submodularity intuition (diminishing returns)
  - Connection to total correlation
  - Why this matters for information dynamics
- **Rewrite needed:** SIGNIFICANT - check if existing refs are relevant
}

\subsection{Marginal Entropy Conservation (15 min)}

\notes{
**Snippet: `marginal-entropy-conservation.md`**
- **Status:** ❌ NEEDS CREATION
- **Source reference:** TIG paper
- **Needs:**
  - Statement of conservation constraint
  - Why this emerges from axioms
  - Physical/information-theoretic interpretation
  - Connection to constraints in dynamics
- **Rewrite needed:** N/A - create from scratch
- **CRITICAL:** This was missing from information-theory-overview.md review
}

\section{Planned Structure}

\subsection{Introduction (5 min)}

\notes{
- Recap: Lecture 1 covered exponential families and Fisher information
- Today: The axioms that make TIG unique
- From general principles to specific framework
}

\subsection{Baez Information Loss Axioms (20 min)}

\notes{
\include{_physics/includes/baez-information-loss.md}
}

\subsection{The Fourth Axiom: Information Conservation (20 min)}

\notes{
\include{_information-game/includes/information-conservation-axiom.md}
}

\subsection{Multi-Information and Submodularity (15 min)}

\notes{
\include{_information-game/includes/submodularity-multi-information.md}
}

\subsection{Wrap-up (5 min)}

\notes{
- Summary: Four axioms define the game
- Next lecture: What dynamics emerge from these axioms?
- Problem set 2 assigned
}

\section{Problems and Exercises}

\notes{
**Problem Set 2:** ⚠️ NEEDS CREATION
- Verify functoriality for simple examples
- Compute multi-information for Gaussian distributions
- Explore submodularity properties
- Check marginal entropy conservation in examples
}

\section{Implementation Status}

\notes{
- [x] Create baez-information-loss.md snippet (COMPLETED - in _physics/includes/)
- [x] Create information-conservation-axiom.md snippet (COMPLETED - in _information-game/includes/)
- [x] Create submodularity-multi-information.md snippet (COMPLETED - in _information-game/includes/)
- [ ] Create problem set 2
- [ ] Create slide deck
- [ ] Test lecture flow

**Core lecture content complete:** All three axiom snippets ready and integrated (~560 lines total).
}

\thanks

\references


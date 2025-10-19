---
title: "Lecture 2: The Four Axioms and Information Loss"
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

\subsection{Review (5 min)}

\notes{
- Quick recap of Lecture 1
- Exponential families and FIM
}

\subsection{The Four Axioms (20 min)}


\include{_physics/includes/four-axioms.md}


\subsection{Baez Information Loss Framework (20 min)}

\include{_physics/includes/baez-information-loss.md}

\subsection{Submodularity and Conservation (15 min)}

\include{_physics/includes/submodularity-multi-information.md}
\include{_physics/includes/marginal-entropy-conservation.md}

\subsection{Wrap-up (5 min)}

- How axioms lead to dynamics
- Preview: Information Relaxation Principle

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
- [ ] Create four-axioms.md snippet
- [ ] Create baez-information-loss.md snippet
- [ ] Create submodularity-multi-information.md snippet
- [ ] Create marginal-entropy-conservation.md snippet
- [ ] Create problem set 2
- [ ] Create slide deck
- [ ] Prepare category theory intuition (keep accessible)
}

\thanks

\references


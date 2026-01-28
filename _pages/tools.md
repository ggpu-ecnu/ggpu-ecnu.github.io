---
layout: archive
title: "Tools"
permalink: /tools/
author_profile: true
---

Here are some of the tools I have been involved in developing:

*   **SimpleCAR**: A very strong SAT-based hardware model checker. The key idea is to maintain two sequences (Up/Under approximation chains) that do not need to obey the inclusion property in IC3.
    *   [Link to SimpleCAR on GitHub](https://github.com/lijwen2748/simplecar)

*   **Aalta**: An LTL-SAT solver for Linear temporal Logic. The theory behind this tool can be found in the earlier paper TIME13 (LTL Satisfiability Checking Revisited, https://www.cs.rice.edu/~vardi/papers/time13.pdf). The theory is very interesting, and it reveals the new mathematical property that an infinite trace satisfying an LTL formula can be reduced to a proof obligation set which can be represented by a Boolean formula. This mathematical property can be applied to all kinds of LTL-related problems, like the synthesis and satisfiability of LTL.
    *   [Link to Aalta on GitHub](https://github.com/lijwen2748/aalta)

*   **Stoat**: A model-based App testing tool for fuzzing Android App. The idea is to construct a transition model from any given App, and then to guide the search space of the APP based on the model of APP. The idea is simple but has been successfully applied to find the bugs in the popular APPs like WeChat and TikTok.
    *   [Link to Stoat on GitHub](https://github.com/tingsu/Stoat)

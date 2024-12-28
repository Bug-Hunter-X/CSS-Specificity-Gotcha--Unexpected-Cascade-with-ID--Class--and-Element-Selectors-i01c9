# CSS Specificity Gotcha: Unexpected Cascade with ID, Class, and Element Selectors

This repository demonstrates an uncommon CSS specificity issue that can lead to unexpected behavior. The problem arises when combining ID, class, and element selectors in a way that doesn't follow the developer's intuition of selector specificity.

The `bug.css` file contains the problematic CSS code, showing how the seemingly most specific selector might not always apply. The `bugSolution.css` file demonstrates several approaches to solving this issue and offers clarifying comments.  The problem is subtle and related to order of cascading rules.
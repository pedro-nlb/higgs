# Title

Some description of the content here.

## About the preamble

### General things
- Table of contents is limited to secction titles.
- One can write to do notes with \todo{ ... }.

### Theorem environments
All numbered together and according to section:
- \theoremstyle{plain}: Theorem (thm), Lemma (lm), Proposition (prop), Corollary (cor), Conjecture (conj) and Fact (fact).
- \theoremstyle{definition}: Definition (defn) and Example (exa).
- \theoremstyle{remark}: Remark (rem), Notation (nota), Question (q) and Exercise (exe).
Cross-referencing is possible with \Cref{label} or \cref{label}, depending on whether we want the first letter capitalised or not.

### Custom numbered theorem environments
Same as the ones above but with an extra "c" in front, e.g. Theorem (cthm).
The syntax is \begin{cthm}{desiredNumbering}[Name of the theorem].
These theorem environments can also be cross-referenced with \Cref{label} or \cref{label}.

### Unnumbered theorem environments
Same as the ones above but with an extra "u" in front, e.g. Theorem (uthm).
No cross-referencing in this case.

### Font definitions
- Mathscr (usually for sheaves): \sA, where A can be almost any letter. Exceptions: \E, \F, \G, \hom, \I, \L, \M and \O.
- Mathcal: \calA. Exceptions: \U, \X and \Y.
- Mathbb: \bbA. Exceptions: \A, \C, \D, \Gm, \k, \N, \P, \Q, \R, \V and \Z.
- Boldfont (usually for categories): \bfA. Exceptions: \Cat, \Coh, \Db, \K, \Mod, \PSh, \QCoh, \Set, \Sh, \Top and \Vec.
- Mathfrak (usually for ideals): only \a, \b, \c, \d, \e, \m and \n.

### Coloured theorem environments
These are similar to the usual ones, but the color of the title of the environment changes:
- \theoremstyle{darkgreentheorem} is a dark green version of \theoremstyle{plain}.
- \theoremstyle{darkbluedefinition} is a dark blue version of \theoremstyle{definition}.
- \theoremstyle{darkredexample} is a dark red version of \theoremstyle{definition}.
To activate them, uncomment the corresponding lines in the preamble.

### Open and closed immersions in tikzcd
With option [open] and [closed] respectively.

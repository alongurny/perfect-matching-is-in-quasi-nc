**Abstract**

This is a summary of *"Bipartite Perfect Matching is in Quasi-NC"* by Fenner, Gurjar, and Thierauf.

We will show an algorithm for perfect matching in bipartite graphs that runs in $\mathsf{quasi-NC^2}$, for 
both the decision and search problems.

This is almost a complete de-randomization: it gives time $\mathcal{O}(2^{O(\log^2 n)}) = \mathcal{O}(n^{O(\log n)})$

**Compile from source**
I used the VScode LaTeX Workshop extension
by James Yu to generate the latex.
The LaTeX command is latexmk:["-synctex=1","-interaction=nonstopmode","-file-line-error","-shell-escape","-pdf","-outdir=%WS1%/src","%WS1%/src/summary"]

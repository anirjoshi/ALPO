# ALPO: Anytime Local Pareto-Optimality

This artifact is the prototype tool ALPO. This is the tool accompanying the paper titled `Locally Pareto-Optimal Interpretations for Black-Box Machine Learning Models`. We note that internet connection would be needed for running the tool, as it uses datasets from the UCI repository which are large to include in the Docker environment.

The tool has two phases, in the first phase multi-objective monte-carlo tree search is executed, and in the second phase a SAT based verification is executed. We also have the max-sat based solution Synplicate as a part of this artifact. For more details on these procedures, we refer the reader to the paper.

In this artifact we first explain the commands needed to execute the tool. Then we walk-through the creation of a new benchmark. Also, a preliminary documentation of the tool is presented in docs/. To open this, open the file docs/html/index.html in a web-browser. The readme in the following DOI contains all the links.

DOI: https://doi.org/10.5281/zenodo.15847338


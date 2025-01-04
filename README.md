# Undergraduate Computational Macro Notebooks
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jlperla/undergrad_computational_macro/HEAD)
This repository is a public notebook repo associated with the [Undergraduate Computational Macro](https://jlperla.github.io/undergrad_computational_macro/)

## Installation
Ensure that `IJulia` is installed (e.g., `julia -e 'using Pkg; Pkg.add(["IJulia", "Revise"]); Pkg.build("IJulia");'` or `] add IJulia Revise` in the REPL).
Then instantiate the environment with
```bash
julia --project --threads auto -e 'using Pkg; Pkg.instantiate();'
```
Or after starting Julia with the project file activated, run `] instantiate`.
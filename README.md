# HelloJulia.jl

To run the tutorials provided in this repository:

### Beginner instructions

- If necessary, install [Julia 1.6](https://julialang.org/download/)
  on your machine

- To get start the so-called REPL, open the Julia 1.6
  application. This should run the Julia in command-line environment
  specific to your operating system (e.g., a unix shell) so that your
  see a the prompt `julia >`.

- Type the following at the `julia>` prompt:

```julia
using Pkg
Pkg.add(url="https://github.com/ablaom/HelloJulia.jl")

using HelloJulia
go()
```

- This should launch a Juptyer notebook session in your browser. Now
  choose one of the folders in the list, say "lightning_tour", and
  from the directory that opens, select the file with the `.ipynb`
  extension (such as `lightning_tour.ipynb`).
  
If for any reason you cannot run the notebook, you can inspect a
static version of the notebook by intead opening the file with the
`.md` extension.

### For more experienced users

Clone this repo locally and navigate to the appropriate subfolder of
`/tutorials`. Open the file with `.jl` extension in your Julia-enabled
IDE.


| Linux | Coverage |
| :------------ | :------- |
| [![Build Status](https://github.com/ablaom/HelloJulia.jl/workflows/CI/badge.svg)](https://github.com/ablaom/HelloJulia.jl/actions) | [![Coverage](https://codecov.io/gh/ablaom/HelloJulia.jl/branch/master/graph/badge.svg)](https://codecov.io/github/ablaom/HelloJulia.jl?branch=master) |

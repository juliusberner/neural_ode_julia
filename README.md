# Neural Differential Equations in Julia
> Exploring the [Flux.jl](https://github.com/FluxML/Flux.jl) and [DiffEqFlux.jl](https://github.com/JuliaDiffEq/DiffEqFlux.jl) packages. Material for the [VSM Student Retreat 2020](https://www.vsmath.at/academics/student-retreats/) 

## Local install

* [Install Julia](https://julialang.org/downloads/platform/)
* [Start interactive session (REPL)](https://docs.julialang.org/en/v1/manual/getting-started/)
* [Create new enviroment](https://docs.julialang.org/en/v1/stdlib/Pkg/)

 ```
 ]
 activate my_env
 ```

* [Install IJulia Notebooks and other required packages](https://github.com/JuliaLang/IJulia.jl)

 `add IJulia, DiffEqFlux, DifferentialEquations, Plots, Optim, Interact`

* Exit the package manager (ctrl+C) and start the notebook

 ```
 using IJulia
 notebook(dir="./path_to_my_env")
 ```

## Cloud Solutions

* [JuliaBox](https://www.juliabox.com/)
* [Julia in Google Colab](https://discourse.julialang.org/t/julia-on-google-colab-free-gpu-accelerated-shareable-notebooks/15319)




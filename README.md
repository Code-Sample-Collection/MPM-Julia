# MPM-Julia
Julia implementation of the material point method (MPM), see the following paper for detail

S. Sinai, V.P. Nguyen, C.T. Nguyen and S. Bordas. [Programming the Material Point Method in Julia.][mpm-in-julia]
Advances in Engineering Software,105: 17--29, 2017.

> The code was written 2 years ago and thus not compatible to the current Julia version.

[This branch `julia-LTS`][julia-LTS] contain codes works well on Julia 1.6+ (test on julia 1.6.4).


```julia
git clone -b julia-lts --single-branch https://github.com/JuliaPapers/MPM-Julia.git
cd MPM-Julia

julia
] activate .
instantiate

cd("Classic_2D_2Disk")  # Or other sub-dir
include("Main.jl")
```

[julia-LTS]: https://github.com/JuliaPapers/MPM-Julia/tree/julia-lts
[mpm-in-julia]: https://doi.org/10.1016/j.advengsoft.2017.01.008

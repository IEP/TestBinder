# TestBinder

To test Binder running Julia's notebook, there are few steps that you need to follow:

1. Create project file, _Project.toml_ by issuing the command
```
julia> ]activate .
```
2. Then add the libraries you want to use, i.e. Plots
```
julia> ]add Plots
```
3. Then add Julia version to _Project.toml_, i.e Julia 1.1
```
[compat]
julia = "~1.1"
```
The configuration will limit the version to be 1.1 <= version <= 1.2. See [Compatibility](https://julialang.github.io/Pkg.jl/v1/compatibility/) for informations.
4. Create your notebook by using Jupyter.
5. Copy the URL of the Github repo into Binder.
6. Done.

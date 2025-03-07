# ManifoldDiff

The package __ManifoldDiff__ aims to provide automatic calculation of Riemannian gradients of functions defined on manifolds. It builds upon [`Manifolds.jl`](https://github.com/JuliaManifolds/Manifolds.jl).

## Naming scheme

Providing a derivative, differential or gradient for a given function, this package adds that information to the function name.
For example

* `grad_f` for a gradient ``\operatorname{grad} f``
* `differential_f` for ``Df`` (also called pushforward)
* `differential_f_variable` if `f` has multiple variables / parameters, since a usual writing in math is ``f_x`` in this case
* `adjoint_differential_f` for pullbacks
* `adjoint_differential_f_variable` if `f` has multiple variables / parameters
* `f_derivative` for ``f'``

the scheme is not completely fixed but tries to follow the mathematical notation.

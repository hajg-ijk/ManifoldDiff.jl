# Different library functions

Documentation for `ManifoldDiff.jl`'s methods and types for finite differences and automatic differentiation.

## Derivatives

```@autodocs
Modules = [ManifoldDiff]
Pages = ["derivatives.jl"]
Order = [:type, :function, :constant]
Private = true
```

## Differentials and their adjoints

```@autodocs
Modules = [ManifoldDiff]
Pages = ["adjoint_differentials.jl"]
Order = [:type, :function, :constant]
Private = true
```

```@autodocs
Modules = [ManifoldDiff]
Pages = ["differentials.jl"]
Order = [:type, :function, :constant]
Private = true
```

```@autodocs
Modules = [ManifoldDiff]
Pages = ["diagonalizing_projectors.jl"]
Order = [:type, :function, :constant]
Private = true
```

## Gradients

```@autodocs
Modules = [ManifoldDiff]
Pages = ["gradients.jl"]
Order = [:type, :function, :constant]
Private = true
```

## Jacobi fields

```@autodocs
Modules = [ManifoldDiff]
Pages = ["Jacobi_fields.jl"]
Order = [:type, :function, :constant]
```

## Riemannian differentials

```@autodocs
Modules = [ManifoldDiff]
Pages = ["riemannian_diff.jl"]
Order = [:type, :function, :constant]
```

## Manifold-specific specializations

```@autodocs
Modules = [ManifoldDiff]
Pages = ["manifolds.jl"]
Order = [:type, :function, :constant]
```

## Differentiation backends

### EmbeddedDiff

```@autodocs
Modules = [ManifoldDiff]
Pages = ["embedded_diff.jl"]
Order = [:type, :function, :constant]
```

### ForwardDiff.jl

```@autodocs
Modules = [ManifoldDiff]
Pages = ["forward_diff.jl"]
Order = [:type, :function, :constant]
```

### FiniteDifferenes.jl

```@autodocs
Modules = [ManifoldDiff]
Pages = ["finite_differences.jl"]
Order = [:type, :function, :constant]
```

## Internal functions

```@autodocs
Modules = [ManifoldDiff]
Pages = ["ManifoldDiff.jl"]
Order = [:type, :function, :constant]
Private = true
Public=false
```

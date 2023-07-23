# MyPublicJuliaRegistry

My public Julia registry. Created using [LocalRegistry.jl](https://github.com/GunnarFarneback/LocalRegistry.jl).

To install this registry, run the following command in the Julia pkg REPL (once per Julia installation):

```
pkg> registry add https://github.com/cossio/MyPublicJuliaRegistry.git
```

This registry contains both public and private packages. Private repos use the `git@github.com:...` url format. See the [LocalRegistry.jl docs](https://github.com/GunnarFarneback/LocalRegistry.jl/blob/master/docs/ssh_keys.md) for more info.
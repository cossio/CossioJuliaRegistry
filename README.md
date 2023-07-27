# CossioJuliaRegistry

My public Julia registry. Created using [LocalRegistry.jl](https://github.com/GunnarFarneback/LocalRegistry.jl).

To install this registry, run the following command in the Julia pkg REPL (once per Julia installation):

```
pkg> registry add https://github.com/cossio/CossioJuliaRegistry.git
```

This registry contains both public and private packages. Private repos use the `git@github.com:...` url format. See the [LocalRegistry.jl docs](https://github.com/GunnarFarneback/LocalRegistry.jl/blob/master/docs/ssh_keys.md) for more info. 

* Some public repos may also use `git@github.com:...` URLs, and you need a SSh key associated to your GitHub account to install them through this registry.
* For private repos, your SSH key needs to be added to the corresponding repo to gain access.

This registry uses [`RegistryCI`](https://github.com/JuliaRegistries/RegistryCI.jl) for integrity checks after each commit using a GitHub Actions workflow.
# CossioJuliaRegistry

My public Julia registry. Created using [LocalRegistry.jl](https://github.com/GunnarFarneback/LocalRegistry.jl).

To install this registry, run the following command in the Julia pkg REPL (once per Julia installation):

```
pkg> registry add https://github.com/cossio/CossioJuliaRegistry.git
```

This registry contains **only public packages**, and the dependencies between them. Every entry points at a public repo under [github.com/cossio](https://github.com/cossio) via an `https://` URL, so no SSH key or other credential is needed to install anything from it.

Private packages are deliberately not registered here. They vendor their dependencies in-repo instead, so they resolve without needing a registry entry.

This registry uses [`RegistryCI`](https://github.com/JuliaRegistries/RegistryCI.jl) for integrity checks after each commit using a GitHub Actions workflow.
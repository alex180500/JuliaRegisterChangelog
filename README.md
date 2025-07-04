# JuliaRegisterChangelog

A reusable GitHub Workflow for [Julia](https://julialang.org/) packages that automates:
1. Detect [`Project.toml`](https://pkgdocs.julialang.org/v1/toml-files/#The-version-field) version bumps following Julia's own SemVer conventions.
2. Generate a changelog automatically using [Conventional Commits](https://www.conventionalcommits.org/) and [conventional-changelog](https://github.com/conventional-changelog/conventional-changelog).
3. Trigger [JuliaRegistrator](https://github.com/JuliaRegistries/Registrator.jl) commenting on the latest commit to register the package and correctly formats the changelog.


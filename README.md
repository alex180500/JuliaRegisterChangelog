# JuliaRegisterChangelog

A reusable GitHub Workflow for [Julia](https://julialang.org/) packages that automates:
1. Detect [`Project.toml`](https://pkgdocs.julialang.org/v1/toml-files/#The-version-field) version bumps following Julia's own SemVer conventions.
2. Generate a Conventional Commits changelog  
3. Trigger JuliaRegistrator via commit comment

This workflow checks for version changes in the Project.toml file and, if a change is detected, generates a changelog using all conventional commits and registers the package with JuliaRegistrator by posting a comment on the latest commit.

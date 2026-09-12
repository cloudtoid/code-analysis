# Cloudtoid.CodeAnalysis

Shared C# analyzer configuration for projects that use Cloudtoid's coding conventions. The package brings together StyleCop and Visual Studio threading analyzers with a common ruleset and build settings.

## Install

Requires a project targeting .NET 10 or later.

```sh
dotnet add package Cloudtoid.CodeAnalysis
```

For a library, keep this build-time dependency private by adding `PrivateAssets="all"` to its `PackageReference`.

## What it configures

- Installs StyleCop and Visual Studio threading analyzers.
- Imports the Cloudtoid ruleset and StyleCop configuration during builds.
- Enables warnings as errors.

Build your project after installation to see diagnostics. Review the rules before adopting the package in an existing codebase: warnings can become build failures.

[Source and rules](https://github.com/cloudtoid/code-analysis) · [Report an issue](https://github.com/cloudtoid/code-analysis/issues) · [MIT license](https://github.com/cloudtoid/code-analysis/blob/main/LICENSE)

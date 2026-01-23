RudiRonsoni - C# Data Structures and Algorithms

This repository contains implementations, exercises, tests, and benchmarks for common data structures and algorithms.

Quick start

- Restore dependencies:

```bash
dotnet restore
```

- Build:

```bash
dotnet build
```

- Run tests:

```bash
dotnet test
```

Project layout

- `DSA/Algorithms` - algorithm library (libraries target `netstandard2.1`)
- `DSA/DataStructures` - data structure implementations
- `Exercises` - exercise implementations and demos
- `*Benchmarks` - runnable benchmark projects (target `net10`)
- `*Tests` - test projects (target `net10`)

Namespace convention

All namespaces are prefixed with `RudiRonsoni` and organized by feature (e.g., `RudiRonsoni.Algorithms.Sorting`, `RudiRonsoni.DataStructures.Trees`, `RudiRonsoni.Exercises.Arrays.Sorting`).

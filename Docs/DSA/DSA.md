# DSA taxonomy

This document maps repository folders to feature-driven namespaces with root `RudiRonsoni`.

Examples:

- `DSA/Algorithms` -> `RudiRonsoni.Algorithms`
- `DSA/Algorithms/Sorting` -> `RudiRonsoni.Algorithms.Sorting`
- `DSA/DataStructures/Trees` -> `RudiRonsoni.DataStructures.Trees`
- `Exercises/Arrays` -> `RudiRonsoni.Exercises.Arrays`

Migration notes: use IDE rename/refactor to migrate namespaces to the feature-driven convention. Libraries target `netstandard2.1`; runnable projects and tests target `net10`.

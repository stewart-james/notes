## Default search order

MSBuild's default search order is

- Files from the current project – indicated by `{CandidateAssemblyFiles}`.
- `$(ReferencePath)` property that comes from .user/targets file.
- `$(HintPath)` indicated by reference item.
- Target framework directory.
- Directories found in registry that uses AssemblyFoldersEx Registration.
- Registered assembly folders, indicated by `{AssemblyFolders}`.
- `$(OutputPath)` or `$(OutDir)`
- GAC
- The reference item include attribute as if it were a complete file name.
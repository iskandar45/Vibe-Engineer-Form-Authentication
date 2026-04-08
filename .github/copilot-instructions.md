# Vibe-Engineer-Form-Authentication Workspace Instructions

## Purpose
This workspace is for the `Vibe-Engineer-Form-Authentication` backend authentication project.
It is currently minimal: only `README.md` exists in the repository at this time.

## Project context
- Project name: Vibe-Engineer-Form-Authentication
- Domain: backend authentication
- Inferred stack: .NET / C# (based on the workspace task configuration)
- Current state: no `.sln`, `.csproj`, or source code files are present in the workspace

## Primary guidance for the agent
- When asked to implement or modify functionality, first confirm the intended source layout if code files are missing.
- Prefer asking the user for project files or the expected repository structure before generating large code changes.
- Use the available build command when validating new or existing .NET code.
- If the user wants to add a new backend component, keep it consistent with typical .NET authentication service patterns.

## Build command
- `dotnet build /property:GenerateFullPaths=true /consoleloggerparameters:NoSummary`

## Notes for future work
- If source files are added, update this instruction file to include the actual project file names and commands.
- If tests are introduced, add `dotnet test` usage and any test folder conventions.
- Keep guidance focused on the current repo state: minimal project scaffold, no existing code to inspect.

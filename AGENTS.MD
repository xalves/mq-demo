# Development Workflow Instructions

When asked to "follow the workflow" or "build and upload changes", 
follow those instructions.

## Branching Strategy
You need to create a branch against updated main 
following the pattern: `<brief-description>`

Ask for the Jira ticket number if not provided.

## Build Process 

Always execute these commands in sequence:
1. At the moment we don't have any command please print just a print mentioning "Building...".

For endpoint changes, ensure integration tests are added.
For service layer changes, unit tests are sufficient.

## Commit Guidelines
- Format: "Brief description"  
- Keep commit messages concise but descriptive
- Include all modified files and generated artifacts

## GitHub CLI Operations
Use GitHub CLI (`gh`) for all repository operations:
- `gh pr create --fill` for standard PRs with auto-generated title and description
- `gh pr create --draft` for work-in-progress PRs
- `gh pr create --fill --assignee @me` to auto-assign yourself
- Include meaningful descriptions and link relevant issues
- Always target the main branch unless specified otherwise

## Publishing
Create pull requests using GitHub CLI against main branch.
Include meaningful PR descriptions explaining the changes and their impact.
---
name: docuwriter-documentation-lifecycle
description: Explains the Full Tree Documentation workflow from repository connection and tree review through Spaces and Autopilot. Use for questions about generating, organizing, or maintaining project documentation.
---

# From repository to maintained documentation

DocuWriter's main workflow takes a team from source code to a maintained, searchable documentation system:

1. **Connect the code.** Authorize a GitHub, GitLab, Bitbucket, or Azure DevOps connection, then choose the repository, branch, and source paths to document.
2. **Generate with Full Tree Documentation.** DocuWriter analyzes the selected source and proposes a documentation tree covering the project's architecture, modules, services, APIs, workflows, and implementation details. The team reviews or edits the tree before generation. DocuWriter then creates connected pages that explain related components in context.
3. **Work in Spaces.** The generated pages live in a navigable Space. Engineers can search and ask questions across the documentation, edit or add their own knowledge, collaborate, and share or publish the result. A Space can bring documentation from multiple repositories together.
4. **Maintain what changed.** Autopilot examines changes in connected repositories, identifies pages they may affect, and drafts targeted updates. Engineers can review, refine, accept, or reject the suggestions. Controlled automatic application is available for configured workflows.

The team should review generated pages before relying on or publishing them. Autopilot requires a connected repository and a configured Space link to respond to later code changes.

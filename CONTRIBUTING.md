<!-- SPDX-License-Identifier: CC-BY-4.0 -->

# Contributing

Thanks for improving this training repository. The goal is simple: examples that students can copy into any repository and run for free.

## How to propose a change
1. Fork the repo and create a branch.
2. Keep examples small and beginner friendly.
3. Open a pull request that explains what the student will learn2.

## Style
- One purpose per workflow. Prefer short names and clear comments.
- Use official or well maintained actions. Pin by major version (for example `@v4`).
- Show minimal permissions:
  ```yaml
  permissions:
    contents: read
  ```
- Prefer caches for speed when it helps beginners.
- Add a brief header comment at the top of each workflow that states the lesson purpose.

## Commit messages
Use concise, imperative summaries. Examples: `add python test workflow`, `teach artifact upload`.

## License and provenance
By contributing you agree that code and workflows are licensed under Apache-2.0. Documentation is CC BY 4.0. Add an SPDX header to new files:
- YAML and code: `# SPDX-License-Identifier: Apache-2.0`
- Markdown docs: `<!-- SPDX-License-Identifier: CC-BY-4.0 -->`

## Pull request checklist
- [ ] Runs pass in your fork
- [ ] Uses free actions only
- [ ] Minimal `permissions` set
- [ ] Clear comments at top describing the lesson
- [ ] README or page link updated if needed

## Code of conduct
Be kind. Keep feedback specific and actionable. Assume good intent.


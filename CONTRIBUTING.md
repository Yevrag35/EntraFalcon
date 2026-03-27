# Contributing to EntraFalcon

Thank you for considering a contribution to EntraFalcon.

Contributions are welcome, and these guidelines are intended to help keep the review process simple and the project maintainable.

## General Expectations

- Keep contributions focused and relevant to the project.
- Prefer changes with clear practical value for users.
- For larger changes, open an issue first to discuss the idea before starting implementation.
- Keep pull requests small and focused on a single change.
- Do not include unrelated refactoring or reformatting.

## AI-Assisted Contributions

AI-assisted contributions are allowed, but their use must be disclosed clearly in the pull request.

Please include:
- which tool was used
- what level of manual review and testing was performed

AI-generated changes may be declined if they significantly increase review effort or do not show sufficient manual validation.

## Low-Value Contributions

To keep the review process efficient, low-value contributions may not be accepted. This includes, for example:
- typo-only fixes
- very small cosmetic changes with no meaningful impact
- minor style adjustments without functional or maintainability benefit
- bulk AI-generated cleanup changes with limited value

## Pull Requests

When opening a pull request:
- describe the problem being solved
- explain the benefit of the change
- keep the scope as small as reasonably possible
- mention any testing that was performed

## Compatibility, Dependencies, and Performance

Please keep changes compatible with Windows PowerShell 5.1.

The project should remain self-contained. Do not introduce external dependencies. This also includes externally loaded resources such as JavaScript files, stylesheets, or similar assets.

Please also consider performance impacts. EntraFalcon may be used in very large tenants, for example with 200,000 objects, so changes should avoid unnecessary overhead, repeated lookups, or patterns that scale poorly.
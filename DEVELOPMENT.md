# Development record

## Bounded version 1.0.0 scope

Record opening dates and print plain labels with the manufacturer guidance you supply. No guessed expiration dates.

Manufacturer instructions remain authoritative. This tool records what you supply and never calculates an expiration date.

This implementation uses a dependency-free static browser application. The source modules are readable; the release build inlines them and CSS into one offline entry point. Data is a strictly validated versioned JSON library in localStorage, with explicit saves and whole-library replacement imports. No server database or account exists.

## Acceptance before release or Gold

- Exercise add, edit, search, photos, deletion confirmation and undo, cancellation, print selection and backup round trips in actual browsers.
- Verify invalid imports, duplicate IDs, wrong fields, image payload limits, text injection, storage denial/quota, corrupt stored bytes and cross-tab write races preserve current data.
- Open the exact release ZIP's extracted `index.html` over file protocol while offline; verify local HTTP fallback and backup migration.
- Review keyboard focus, labels, visible errors, 390 px layout and desktop layout; inspect print/PDF output with long notes and multiple entries.
- Run tests, syntax check, build and independent review. Preserve review evidence and resolve actionable findings before release.
- Verify exact remote commit, CI/CodeQL, annotated tag, ZIP hash, Pages and Forge links through the established portfolio release process. Gold remains unassigned until these and the bounded scope are assessed.

No shared Forge catalog, release register or owner files are modified by this project build.

# Organization defaults

Default community health files for every repository in this organization that has none of its own.

- `.github/ISSUE_TEMPLATE/factory-feature.yml` and `factory-bug.yml`: the issue forms every piece of work starts from. Sections: Story or Problem, Acceptance criteria, Decisions already made, Scope. A planning skill turns such an issue into a specification, plan and tasks without asking questions first.
- `.github/ISSUE_TEMPLATE/config.yml`: blank issues are off, so the forms are always used.

A repository that needs different forms adds its own `.github/ISSUE_TEMPLATE` folder; GitHub then ignores these defaults for that repository. This repository has to be public for the defaults to apply, so keep it free of anything internal.

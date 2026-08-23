# Meeplia Organization Metadata Navigation

## Canonical program

- Internal goal:
  [`Meeplia/meeplia-hub/docs/goals/meeplia-platform-v2.md`](https://github.com/Meeplia/meeplia-hub/blob/main/docs/goals/meeplia-platform-v2.md)
- Public repository responsibility:
  [README.md](README.md)

## Responsibility

Own only public-safe organization profile content, security and support policy,
issue templates, pull-request templates, and shared contribution guidance. Do
not place product runtime code, private roadmaps, credentials, internal incident
details, customer data, private repository evidence, or launch configuration
here.

## Validation

This repository has no runtime test suite. For metadata changes run:

```bash
git diff --check
```

Validate changed YAML templates with a safe YAML parser when their structure
changes, and preview public Markdown before merge.

## Security boundaries

- Assume every committed byte is public.
- Never include secrets, real environment values, private vulnerability
  details, personal information, payment data, internal logs, or non-public
  launch instructions.
- Keep source, comments, issues, pull requests, templates, and documentation in
  English.
- Direct repository-specific implementation work to its owning repository and
  architecture changes to the private governance hub.

## Current workstream state

Platform V2 governance is `IN_PROGRESS`. This repository has no runtime
implementation task; its next work is limited to public-safe security policy,
templates, and contribution guidance required by the operations/security
workstream.

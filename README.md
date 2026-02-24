# Platform Hub Library

A library of example templates and policies for use in Octopus Deploy's Platform Hub.

## Usage

This repository is _*NOT*_ meant to be used as your Platform Hub git repo.  

- The structure of this repository is intentionally different than what Platform Hub expects.  The Platform Hub git repo is designed for usability.  This repository is designed for discoverability.
- Process Templates and Project Templates are much more complex than step templates, trying to create a generic template that'll work for every instance and every use case is not feasible.

When you find a policy or template you like copy the `.ocl` file into the appropriate folder in your Platform Hub repo.

- **Policies** - copy into `.octopus/policies`
- **Process Templates** - copy into `.octopus/process-templates`
- **Project Templates** - copy into `.octopus/project-templates`

## Contribution

Read our [contributing guidelines](.github/CONTRIBUTING.md) for information about contributing templates and policies.


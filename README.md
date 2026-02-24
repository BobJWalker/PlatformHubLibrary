# Platform Hub Library

A library of example templates and policies for use in Octopus Deploy's Platform Hub.

## Usage

This repository is _*NOT*_ meant to be used as your Platform Hub git repo.  The structure of this repository is intentionally different than what Platform Hub expects.  The Platform Hub git repo is designed for usability.  This repository is designed for discoverability.

When you find a policy or template you like copy the `.ocl` file into the appropriate folder in your Platform Hub repo.

- **Policies** - copy into `.octopus/policies`
- **Process Templates** - copy into `.octopus/process-templates`
- **Project Templates** - copy into `.octopus/project-templates`

## Contribution

Please contribute to this library!  We want it to be useful for every user of Octopus Deploy's Platform Hub!

The contribution guidelines are below.

- **Octopus Deploy Employees** - Create a branch in this repo and submit a pull request.
- **Everyone Else** - Fork the repository and submit a pull request.

### New Templates and Policies

If you create a new template or policy then please follow these instructions.

1. Create a new folder with the policy or template name in the appropriate Policies, Process Templates, or Project Templates folder.
2. Copy in the `.ocl` of the policy or template into that new folder.
3. Create a `README.md` for the policy or template.  The file should include (templates have been provided for your convenience):
   1. Purpose of the policy or template.
   2. How it is expected to work, include any use cases.
   3. Detail what someone is expected to (if anything) change when they copy it to their instance.
   4. List known limitations about the policy or template.

The goal of the `README.md` file is to provide additional context to everyone that is not part of the description or parameters inside the template or policy.

### Existing Templates and Policies

If you improve or iterate on a policy or template then please follow these instructions.

1. Update the `.ocl` of the policy or template.
2. If you make any meaningful changes then review and update the `README.md` file.  Examples of meaningful changes include:
   1. Adding support for new use cases.
   2. Eliminating a known limitation.
   3. An addition that could cause an unexpected result.

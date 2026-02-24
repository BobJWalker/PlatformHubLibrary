# Library Guidelines

Please review the items below when submitting a PR to this library.

## Background

<!-- Do you have any context to help us understand this change.  Is it to fix a bug, add a new use case to a template or policy, or create an entirely new template or policy to share with the world? -->

## Adding new templates or policies

- [ ] The template or policy is in a dedicated folder
- [ ] I've created the appropriate `README.md` file in that folder
- [ ] The template or policy is new and not a minor variation of an existing one.
- [ ] Naming
  - [ ] The name of the template consistent with the examples already in the library, in style ("Noun - Verb"), layout and casing.
  - [ ] The `.ocl` filename is consistent with the name of the policy or template.  The name will be used as the slug, which is how it will be referenced in other parts of Octopus Deploy.
- [ ] Parameters
  - [ ] All the parameters names are appropriately namespaced with `[TemplateName].[ParameterName]` or `[TemplateAbbr].[ParameterName]`
  - [ ] All the parameters are have a clear and concise label
  - [ ] All parameters have appropriate help text to help consumers
- [ ] For any custom Bash, PowerShell, or Python scripts, I've included appropriate logging to help users debug issues.
- [ ] I'm happy to contribute under the terms of Apache License 2.0.  I've obtained written permission to contribute.

## Updating existing templates or policies 

- [ ] I've reviewed the `README.md` file for the policy or template and made appropriate updates.
- [ ] New Parameters
  - [ ] All the parameters names are appropriately namespaced with `[TemplateName].[ParameterName]` or `[TemplateAbbr].[ParameterName]`
  - [ ] All the parameters are have a clear and concise label
  - [ ] All parameters have appropriate help text to help consumers
- [ ] For any custom Bash, PowerShell, or Python scripts, I've included appropriate logging to help users debug issues.
- [ ] I'm happy to contribute under the terms of Apache License 2.0.  I've obtained written permission to contribute.
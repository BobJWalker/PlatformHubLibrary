# Contribution

Have a great example of a process template, project template or policy you want to share?  Here is how to share it with the world!

The contribution guidelines are below.

- **Octopus Deploy Employees** - Create a branch in this repo and submit a pull request.
- **Everyone Else** - Fork the repository and submit a pull request.

## Licensing

The entire library is covered by [this Apache 2.0 license](https://github.com/OctopusDeploy/Library/blob/master/LICENSE.txt). [This site](http://choosealicense.com/licenses/apache-2.0/) provides a good explanation of what this license provides for you as a contributor. By contributing to this library:

* You will be asked to sign our [Contributor License Agreement (CLA)](https://en.wikipedia.org/wiki/Contributor_License_Agreement) which at the time of writing was [v1.0](https://gist.github.com/PaulStovell/568affdef31fda72d4302615ae9bcbe2). This basically allows us to accept your contribution for which you are claiming full ownership, and then relicense it under [this Apache 2.0 license](https://github.com/OctopusDeploy/Library/blob/master/LICENSE.txt). We cannot accept your contribution without your consent, nor share it with anyone else.
* Your contribution is automatically covered by [this Apache 2.0 license](https://github.com/OctopusDeploy/Library/blob/master/LICENSE.txt) without requiring a header in each file.
* Your contribution is attributed to you (and your organisation) via commits and pull-requests.
* State changes are tracked automatically via commits and pull-requests.

## Repo Structure

This repository is _*NOT*_ meant to be used as your Platform Hub git repo.  

- The structure of this repository is intentionally different than what Platform Hub expects.  The Platform Hub git repo is designed for usability.  This repository is designed for discoverability.
- Process Templates and Project Templates are much more complex than step templates, trying to create a generic template that'll work for every instance and every use case is not feasible.

When you want to contribute a policy or template, make sure you add it to the appropriate folder.

## New Templates and Policies

If you create a new template or policy then please follow these instructions.

1. Create a new folder with the policy or template name in the appropriate Policies, Process Templates, or Project Templates folder.
   1. **Policies** - create a new folder in `policies`
   2. **Process Templates** - create a new folder in `process-templates`
   3. **Project Templates** - create a new folder in `project-templates`
2. Copy in the `.ocl` of the policy or template into that new folder.
3. Create a `README.md` for the policy or template.  The file should include (templates have been provided for your convenience):
   1. Purpose of the policy or template.
   2. How it is expected to work, include any use cases.
   3. Detail what someone is expected to (if anything) change when they copy it to their instance.
   4. List known limitations about the policy or template.

The goal of the `README.md` file is to provide additional context to everyone that is not part of the description or parameters inside the template or policy.

## Existing Templates and Policies

If you improve or iterate on a policy or template then please follow these instructions.

1. Update the `.ocl` of the policy or template.
2. If you make any meaningful changes then review and update the `README.md` file.  Examples of meaningful changes include:
   1. Adding support for new use cases.
   2. Eliminating a known limitation.
   3. An addition that could cause an unexpected result.
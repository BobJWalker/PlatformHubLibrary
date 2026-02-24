# Policy Library

A library of policy to be used with Octopus Deploy's Platform Hub.

## Usage

Find a policy that matches your needs and copy the `.ocl` file to your `.octopus/policies` folder.

## Contribution

Please contribute to this library!  We want it to be useful for every user of Octopus Deploy's Platform Hub!

The contribution guidelines are below.

- **Octopus Deploy Employees** - Create a branch in this repo and submit a pull request.
- **Everyone Else** - Fork the repository and submit a pull request.

### New Policy

If you create a new policy then please follow these instructions.

1. Create a new folder with the policy name in the appropriate folder.
2. Copy in the `.ocl` of the policy into that new folder.
3. Create a `README.md` for the policy.  The file should include the following.  See `ExampleReadMe.md` in this folder.
   1. Purpose of the policy.
   2. How it is expected to work, include any use cases.
   3. Detail what someone is expected to (if anything) change when they copy it to their instance.
   4. List known limitations about the policy.

The goal of the `README.md` file is to provide additional context to everyone that is not part of the description or parameters inside the policy or policy.

### Existing Policy

If you improve or iterate on a policy then please follow these instructions.

1. Update the `.ocl` of the policy.
2. If you make any meaningful changes then review and update the `README.md` file.  Examples of meaningful changes include:
   1. Adding support for new use cases.
   2. Eliminating a known limitation.
   3. An addition that could cause an unexpected result.

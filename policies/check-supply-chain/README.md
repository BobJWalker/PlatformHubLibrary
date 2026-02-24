# Verify Supply Chain template is included

A policy that will ensure the verify build artifacts process template is included in all deployments and is not skipped.

## Use Case

The purpose of this policy is to prevent developers from skipping the supply chain check.

## Assumptions Made

This policy was designed with the following assumptions:

1. The slug of the process template (the file name) is the same as what is in this repo.
2. You only want it to run in project group labeled "Kubernetes" for the `Test`, `Staging`, and `Production` environments.

## Expected Changes

You'll likely need to make the following changes:

1. Change the slug of the process template.
2. Change the scoping.

# MathModpedia - OUCRU Mathematical Modelling Group

An encyclopedia for mathematical modelling from the Mathematical Modelling Group of Oxford University Clinical Research Unit (OUCRU).

# Workflow for contributors

`main` branch will be locked and in read-only mode. You cannot push to this branch. This is to ensure any changes made to the book are thoroughly examined and breaking changes aren't accidentally pushed to `main`. **Pushes are instead performed through pull requests and merges from your development branches**.

Each contributor should setup their own branch with their name for writing/development, e.g. a branch named `tuyen` for Tuyen to write/edit and a branch named `thinh` for Thinh to write/edit. **Be sure to regularly update your branch to match the `main` branch before creating pull requests**. Pull requests will be reviewed by Marc (or others if unavailable), before merging into the `main` branch.

The `main` branch will have a GitHub Action that automatically renders and deploys the book online whenever there's a new pull request merged.

This setup is rather experimental so let's try this framework out and see how it works. Changes can be made afterwards to fit the workflow better.

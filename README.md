# Model CI/CD using GitHub Actions

## What is this project?

Over my career as a programmer I've spent a lot of time working on Continuous Integration and Continuous Deployment on various projects, but the vast majority of that work is hidden behind close doors.

This project is an attempt to capture some of my knowledge in a way that I can share it with the community. Hopefully others will find value in some of the patterns and implementions found here.

## Patterns in use

### Monorepo

The projects contains two different web apps which are deployed independantly, or together.

### Multiple environments

Pull requests are deployed automatically to a test environment.

Commits to the main branch are deployed automatically to the live environment.

### Shared workflow files

Some workflow files reference other workflows to ensure consistent steps.

## Sample web sites

TODO: link to site A test, site B test, site A live and site B live.

## Contributing to this project

I am happy to consider any pull request if you think the implementation or documentation can be improved. I hope this repository can be a living project where the standards evolve and improve over time.

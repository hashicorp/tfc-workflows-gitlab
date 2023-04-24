# Terraform Cloud Workflows for GitLab

This repository provides
a [base template](https://github.com/hashicorp/tfc-workflows-gitlab/blob/ce9a175f0a220556dd0fa297b71a3374b49e41aa/Base.gitlab-ci.yml)
and a
sample [.gitlab-ci.yml](https://github.com/hashicorp/tfc-workflows-gitlab/blob/ce9a175f0a220556dd0fa297b71a3374b49e41aa/.gitlab-ci.yml)
file that demonstrate how to integrate your GitLab CI/CD
pipelines with Terraform Cloud.

## Related Projects

- [tfc-workflows-tooling](https://github.com/hashicorp/tfc-workflows-tooling)
- [tfc-workflows-github](https://github.com/hashicorp/tfc-workflows-github)

## About

These templates utilize custom Docker containers that interact with Terraform Cloud APIs instead of the traditional
Terraform CLI.
The core tooling consists of a containerized Go [application](https://github.com/hashicorp/tfc-workflows-tooling)
designed to work with various CI/CD platforms, including
GitHub Actions and GitLab Pipelines.

## Usage

Our CI/CD template files are designed to be self-contained, with in-place comments providing additional details. Please refer to these comments for more information.


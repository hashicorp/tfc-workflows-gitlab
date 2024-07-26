# UNRELEASED

# v1.3.1
* Fixes message argument to correctly handle multi string values by @Rohlik [#26](https://github.com/hashicorp/tfc-workflows-gitlab/pull/26)
* Bug fixes and enhancements from [tfc-workflows-tooling@v1.3.1](https://github.com/hashicorp/tfc-workflows-tooling/releases/tag/v1.3.1)
* Compiles for Linux regardless of current CPU architecture when using the provided Dockerfile by @ggambetti [hashicorp/tfc-workflows-tooling#113](https://github.com/hashicorp/tfc-workflows-tooling/pull/113)

# v1.3.0
* Adds support for `target` input for `create-run` action by @trutled3 [#97](https://github.com/hashicorp/tfc-workflows-tooling/pull/97)
* Bug fixes and enhancements from [tfc-workflows-tooling@v1.3.0](https://github.com/hashicorp/tfc-workflows-tooling/releases/tag/v1.3.0)

# v1.2.0
* Adds support for save_only, plan_only, and is_destroy options in the create run action by @aaabdelgany. [#17](https://github.com/hashicorp/tfc-workflows-gitlab/pull/17)

# v1.1.1
* Adds new `actions/workspace-output` action to fetch the latest state version output(s) for a given Terraform Cloud Workspace.
* Bug fixes and enhancements from [tfc-workflows-tooling@v1.1.1](https://github.com/hashicorp/tfc-workflows-tooling/releases/tag/v1.1.1) version bump.

# v1.0.3
* Bug fixes and enhancements from [tfc-workflows-tooling@v1.0.3](https://github.com/hashicorp/tfc-workflows-tooling/releases/tag/v1.0.3) version bump
* Updates `.gitlab-ci.yml` template two new jobs. Creation of a merge request comment on job failure and run status check by @mjyocca [#14](https://github.com/hashicorp/tfc-workflows-gitlab/pull/14)

# v1.0.2
* Bug fixes and enhancements from [tfc-workflows-tooling@v1.0.2](https://github.com/hashicorp/tfc-workflows-tooling/releases/tag/v1.0.2) version bump

# v1.0.0

First Release

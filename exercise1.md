CI/CD in Python

# Linting

Linting in python can be done using pylint or mypy. These can be installed similar to installing with npm - using pip install. Alternatively, both of these are integrated into VS code. Settings can be set in .pylintrc.

# Testing

There are different options available for testing in python. Unittest is built into python standard library, which means no need for external installations, but there are also nose/nose2 or pytest. Doing tests in web dev with python is also easy, as both django and flask provide a test framework based on unittest.

# Building

For building, there are 2 good options - setuptools and poetry. Both can be used to create packages, manage dependencies and create virtual environments.

# Alternatives to CI besides jenkins and github actions

Alternatives include Travis CI, which is cloud-hosted and is designed to work with GitHub repos. It is not possible to self-host it. There are also AWS CodePipeline and Azure pipelines. If AWS or Azure are already used in your project, these seem like logical options to use for CI/CD.

# Self-hosted or cloud based?

There are many different things that should be taken into account when deciding to use a self-hosted or a cloud-based environment. For example, if it will be a big project or just a small hobby project. It is also important to consider how many people are developing it, and how many users will the app have. A self-hosted environment requires more configuration, but also provides more freedom to customize your pipeline.

# Environment Setup

## Recommended Setup

* Ubuntu (Current LTS Version)
* [pyenv](https://github.com/pyenv/pyenv) - for python environment management
* [poetry](https://python-poetry.org/) - For project and dependency management
* [docker](https://docs.docker.com/engine/install/ubuntu/)
* CUDA Drivers
* VSCode
* Increase the swap size on you machine to 20GB [tutorial](https://www.digitalocean.com/community/tutorials/how-to-add-swap-space-on-ubuntu-20-04)

## Don't

At Aegion, we don't use `anaconda`. While `anaconda` is a very popular package management system, in order to ensure that all our projects have the the most detailed dependency trees, we recommend the learner to familiarize themselves with `poetry` to ensure that all the dependencies are captured accurately with precise versioning and environment constraints. This is critical as we move prototypes to production.

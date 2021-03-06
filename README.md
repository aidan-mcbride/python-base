# python-base

base python project with tooling to enforce code styles.

## Set-up

1. [Install PDM](https://pdm.fming.dev/#installation)
1. Add your project [metadata](https://peps.python.org/pep-0621/#details) to [`pyproject.toml`](./pyproject.toml). Verify that license, python version, etc. are correct.

1. Install pre-commit hook: `pdm run pre-commit install`

---

## Tools

- Package Manager: [PDM](https://pdm.fming.dev/)

- [Pre-commit](https://pre-commit.com/)

- [Black](https://black.readthedocs.io/en/stable/)
- [iSort](https://github.com/PyCQA/isort)
  - ([black compatibility guide](https://pycqa.github.io/isort/docs/configuration/black_compatibility.html))
- [Pyproject Flake8](https://github.com/csachs/pyproject-flake8)
  - ([black compatibility guide](https://black.readthedocs.io/en/stable/guides/using_black_with_other_tools.html#flake8))
- [Mypy](https://mypy.readthedocs.io/en/stable/index.html)

## Ref Docs

- [hypermodern python series](https://cjolowicz.github.io/posts/hypermodern-python-01-setup/)
- [sourcery - python best practices](https://sourcery.ai/blog/python-best-practices/)

### Tangentially Related Docs

- [git best practices](https://deepsource.io/blog/git-best-practices/)

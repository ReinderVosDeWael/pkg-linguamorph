# CMI-DAIR Template Python Repository

This is a template repository. Below is a checklist of things you should do to use it:

- [x] Run `setup_template.py` to set up the repository.
- [ ] Rewrite this `README` file.
- [ ] Install the `pre-commit` hooks.
- [x] Update the `LICENSE` file to your desired license and set the year.
- [ ] Update the supported versions in `SECURITY.md` or, if not relevant, delete this file.
- [ ] Remove the placeholder src and test files, these are there merely to show how the CI works.
- [ ] Grant third-party app permissions (e.g. Codecov) [here](https://github.com/organizations/cmi-dair/settings/installations), if necessary.
- [ ] Either generate a `CODECOV_TOKEN` secret [here](https://github.com/cmi-dair/flowdump/blob/main/.github/workflows/python_tests.yaml) (if its a private repository) or remove the line `token: ${{ secrets.CODECOV_TOKEN }}`
- [ ] API docs website: After the first successful build, go to the `Settings` tab of your repository, scroll down to the `GitHub Pages` section, and select `gh-pages` as the source. This will generate a link to your API docs.
- [ ] Update stability badge in `README.md` to reflect the current state of the project. A list of stability badges to copy can be found [here](https://github.com/orangemug/stability-badges). The [node documentation](https://nodejs.org/docs/latest-v20.x/api/documentation.html#documentation_stability_index) can be used as a reference for the stability levels.

# Project name

[![Build](https://github.com/cmi-dair/pkg-linguamorph/actions/workflows/test.yaml/badge.svg?branch=main)](https://github.com/cmi-dair/pkg-linguamorph/actions/workflows/test.yaml?query=branch%3Amain)
[![codecov](https://codecov.io/gh/cmi-dair/pkg-linguamorph/branch/main/graph/badge.svg?token=22HWWFWPW5)](https://codecov.io/gh/cmi-dair/pkg-linguamorph)
[![Ruff](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json)](https://github.com/astral-sh/ruff)
![stability-wip](https://img.shields.io/badge/stability-work_in_progress-lightgrey.svg)
[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/cmi-dair/pkg-linguamorph/blob/main/LICENSE)
[![pages](https://img.shields.io/badge/api-docs-blue)](https://cmi-dair.github.io/pkg-linguamorph)

What problem does this tool solve?

## Features

- A few
- Cool
- Things

## Installation

Install this package via :

```sh
pip install linguamorph
```

Or get the newest development version via:

```sh
pip install git+https://github.com/cmi-dair/pkg-linguamorph
```

## Quick start

Short tutorial, maybe with a

```Python
import linguamorph

linguamorph.short_example()
```

## Links or References

- [https://www.wikipedia.de](https://www.wikipedia.de)

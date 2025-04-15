# PyHC Package Repo Template

[![PyHC Community Package badge](https://img.shields.io/badge/PyHC-Community%20Package-brightgreen?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAAGXcA1uAAAAAXNSR0IArs4c6QAAAIRlWElmTU0AKgAAAAgABQESAAMAAAABAAEAAAEaAAUAAAABAAAASgEbAAUAAAABAAAAUgEoAAMAAAABAAIAAIdpAAQAAAABAAAAWgAAAAAAAABIAAAAAQAAAEgAAAABAAOgAQADAAAAAQABAACgAgAEAAAAAQAAABigAwAEAAAAAQAAABgAAAAAEQ8YrgAAAAlwSFlzAAALEwAACxMBAJqcGAAAAVlpVFh0WE1MOmNvbS5hZG9iZS54bXAAAAAAADx4OnhtcG1ldGEgeG1sbnM6eD0iYWRvYmU6bnM6bWV0YS8iIHg6eG1wdGs9IlhNUCBDb3JlIDYuMC4wIj4KICAgPHJkZjpSREYgeG1sbnM6cmRmPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5LzAyLzIyLXJkZi1zeW50YXgtbnMjIj4KICAgICAgPHJkZjpEZXNjcmlwdGlvbiByZGY6YWJvdXQ9IiIKICAgICAgICAgICAgeG1sbnM6dGlmZj0iaHR0cDovL25zLmFkb2JlLmNvbS90aWZmLzEuMC8iPgogICAgICAgICA8dGlmZjpPcmllbnRhdGlvbj4xPC90aWZmOk9yaWVudGF0aW9uPgogICAgICA8L3JkZjpEZXNjcmlwdGlvbj4KICAgPC9yZGY6UkRGPgo8L3g6eG1wbWV0YT4KGV7hBwAABchJREFUSA2VVXtMU1cY/93b29IiUCu0gFA6AtgKxtccG5s6cfEVjJsyJGxONsx8zGQxc26JcVs23YL7x20Y94fbiLhlmmGmMXMx9YVDTSQZ1jgrIEOkCAXBokJLH/fsO7fe+pjZ4yTf/c753o/znQvcW4wxjcA/JtPU8KqqMkjEYH9Wa6G1XVaFoljgnPkbP4LF2wb0uc+zgRodu+n13FX4ZERMN1ew5Z9XsNraQ3RkXAOYPimXNTWdYTurNzE6cghzurJYy2E2sANB5u/kjH9ZZFNf9NoyNnPxGzFpkYifC4Lg7/f0oK35d26CO8+UGhoaNuXRae0LhcACA+r3uBEIBHZztnn0ciPrr0lkvr1mxjobYuaUCAa2IzxYcz/MaCIKK/oZHPRd31P3o9V7w4sZhdNQWrpkM3GqKQ7FUkyBXFmJYUoR5rhK69+BPGxBil6G3d+F1yvLs4jXRxAiAI4dc7LJBXaWmqBUiVuKwcmTJ9R9aGRkZB/vEyzmlCFzEhLXr5goLn/KCp2mBUyrgRQnYrhvFd4us7OvfmqRDQZDsxIShUMhRmMc+W4OCwSuQtAOQxASYZxVDcH+Siz02IZ7UhUJV1H/bIDURoa+V+lc5qFFDPEhwmMOMQ/3hJ8+csR5tqmpGXq9HuXlL93OzrYZH6MXJbW2drnz8yoiyz5Zwha+V0bVMYfI0FoCnarEL4eaeIFeL2gds3OQlFGNzBnrSKafh2gmcKgKCj7T2KjWmrCNFa+bzp5fv0uhbdu2U8Hd3Z4BRZg8FNNGzjBpWNZ4ywOK0ea9tXYNy7OlsdVvruI8ZcDiCAvpqSbMKl4A+9QnId++QSWWcfnaLbjP7YeB2hsYjd4K3ulmrpmUmozNVYsQ79oAlpYAQZIh5IhonpCJLfVxmFf8HOrq6qAkHAgGT2tbGmdFEg0Y/qUIvu44mBykIISgLzoBJjLEZc8tJ7sHlLuk1+lmcy8h7xWXHB47aWyWJLJRmlTZF9HlFFdSt3+gXEXCsqLAhe+V18MGfZPkJIQELQQxXsnxLvE0JBzhcrFO8wNfxJwCBF8ERD/V5BAJtkY50e/fFFSmGgLhBKLNlWXZEQyG42U5DEmSgjqdjl4nnCKD/arOf8JkMOY0FAyd++zTGt4v3gMOQWAigZHvKaV85vH0kgoroTPPRsPxg+vRGlFAgqwKtF5tH7PvmxN4tnSr+MTSyaJmyAlBY4HOvBjam334es3GyPGTDZqVK5aP4zqkq9SRHCkN4DSJDtwoj1JLsNvlclX09fmYwTBGcF1oly52dCPXdkc0D/sxLq4QMoYRunsUA/1c5Q/NtY4huN0dtU7nb7t1OiYVFOR7iLGS4HQsI9pYrlxx+4jIUk0JkQl5eXJ2dp5steax+Hgry8hwsHR9LjPCwRKhZ0kk57BP5R7YB1u2si92KPMiP1NYyLMf3VtXRybZ+7RXrgnH03t7vcqcJ1vShFvediE52YxLXV6UlczBopLFVBoRgRCjgRJAzxskSrpg8pdoa2vBq5WrUZCTJvR0tXBbGqfTiZfLyubSfrvag9FIJPrLSTdphJxkKw6f7UTjqV8xeOkU/KffRZYdoEGBhjSCFKdvBGhzAxd7rZg9RQ+tOARpnB6dPWDGJANkOdLLvfFfp9IQwt8eP3qwauvCpZEPKyFOy4UwpqQWIxcPIXLnID2yRkTCIiR9BIJulDTjaX6TIIqdSvNuDQP1xyFf8E8RP97xsz8zKzufentNuZKqE+6R9kWEeLlE2efZNbJ/vi0Yus7ozRcgjlAGVHqRUtBkUbXbZePMvSIcK3aQ/AGCRAIXGe5RbSolIgJvjjrO5+m+yXSg/xQbZSEfmGyh1zyRggnQngvSQ6IxgoXoUsnKQ99KNs6QUf600ZwoV1axGRsqTlSX6p3weLBgbbCjeZ5usIVk6aJJ1OEI2TDYELYUhKQU+y4yvkHV/V+YO2L82vzDisrcn/5HRf8CON2yWmqX1CEAAAAASUVORK5CYII=)](https://heliopython.org/projects)
[![DOI](https://zenodo.org/badge/954874530.svg)](https://doi.org/10.5281/zenodo.15191528)

## Overview

This repository template created by the [Python in Heliophysics Community (PyHC)](https://pyhc.org) provides a foundation for new Python projects wishing to become PyHC packages. It follows all PyHC standards and best practices, making it easy for developers to start new projects that will integrate well with the PyHC ecosystem.

## How to Use This Template

1. Click the green "Use this template" button at the top of this GitHub repository
2. Select "Create a new repository"
3. Name your new _public_ repo and complete the remaining fields
4. Update the `pyproject.toml` file with your package information
5. Rename the `src/my_pyhc_package` directory to match your package name
6. Start developing your awesome heliophysics package!

## Code Style

All PyHC projects must follow the [PEP 8](https://www.python.org/dev/peps/pep-0008/) style recommendations. This template has been pre-configured to comply with them. Use static analysis tools to identify style deviations, e.g.:
  - Flake8 (what this template was linted with)
  - Pylint
  - Ruff


## Testing

Testing is essential for PyHC packages. This template includes a basic test setup compatible with pytest, although you may use your preferred testing framework.

### Testing Guidelines:
- Write unit tests for individual components (functions, classes)
- Write integration tests that verify interactions between components
- Measure test coverage

As an example, to run tests with pytest:
```bash
# Run all tests
pytest tests/

# Run tests with coverage
pytest --cov=src tests/
```

## Publishing Your Package
It is recommended that PyHC packages publish to both PyPI (pip) and conda.

### Publishing to PyPI

This template includes a GitHub Actions workflow that automatically publishes your package to PyPI when you create a new release on GitHub.

1. Ensure your `pyproject.toml` is properly configured
2. Create a PyPI API token and add it to your repository secrets as `PYPI_API_TOKEN`
3. Create a new release on GitHub
4. The workflow will automatically build and publish your package

For more details, see the [PyPI documentation](https://packaging.python.org/en/latest/tutorials/packaging-projects/).

### Publishing to conda

To make your package available via conda:

1. Create a conda recipe (usually a `meta.yaml` file)
2. Submit your package to conda-forge

For detailed instructions, see the [conda-forge documentation](https://conda-forge.org/docs/maintainer/adding_pkgs.html).

## DOI Integration with Zenodo

To automatically mint DOIs for your releases:

1. Log in to [Zenodo](https://zenodo.org/)
2. Navigate to your GitHub account settings in Zenodo
3. Enable the repository you want to track
4. Create a new release on GitHub
5. Zenodo will automatically mint a DOI for your release

For more detailed instructions, see [this guide](https://github.com/OpenScienceMOOC/Module-5-Open-Research-Software-and-Open-Source/blob/master/content_development/Task_2.md).

## Citation File

This template includes a CITATION.cff file that follows the [Citation File Format](https://citation-file-format.github.io/) specification. Update this file with your project's information to make it easy for others to cite your work.

For more information, see GitHub's [documentation on citation files](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-citation-files).

## Documentation

This template includes a basic `docs/` directory where you can build your documentation. It's recommended to use [Read the Docs](https://readthedocs.org/) for hosting your project documentation, as doing so automatically grants your package inclusion in the [PyHC Documentation Hub](https://heliopython.org/pyhc-docs/).

Alternative documentation systems for Python include:
- Sphinx
- MkDocs
- Jupyter Book

## Code of Conduct

This template includes a Code of Conduct based on the [Contributor Covenant](https://www.contributor-covenant.org/). Please review and modify `CODE_OF_CONDUCT.md` as needed for your project, but ensure it remains compatible with the Contributor Covenant.

## License

This template includes a permissive license. PyHC recommends using permissive open-source licenses such as:
- BSD 3-Clause License
- MIT License
- Apache License 2.0

Copyleft licenses like GPL are not recommended for PyHC projects.

You may choose a different license for your project by updating the `LICENSE` file, but make sure to select an OSI-approved permissive license.

## PyHC Environment Compatibility

The [PyHC Environment](https://github.com/heliophysicsPy/pyhc-docker-environment) is a Dockerized Python environment deployed via Binder that includes all published PyHC packages. When developing your package, we strongly request that you ensure compatibility with this environment.

### Dependency Management:
Substantial prior community work was done to resolve dependency conflicts among PyHC packages to allow them to be imported and used in the same environment.

- Packages that follow [PHEP 3](https://github.com/heliophysicsPy/standards/pull/29) guidelines for dependency management are significantly less likely to introduce conflicts
- To check the allowed version ranges of dependencies, refer to the latest [PyHC Environment dependency spreadsheet](https://github.com/heliophysicsPy/pyhc-docker-environment/tree/main/spreadsheets)
- Note that when dependency conflicts arise, PyHC's Tech Lead will personally work with the affected packages to try to resolve them (inability to resolve will result in the temporary removal of the offending package from the environment)

## PyHC Standards

For the complete set of PyHC standards that packages must follow, please refer to the [PyHC Standards Document](https://github.com/heliophysicsPy/standards/blob/main/standards.md).

## PyHC Submission
Did you make an awesome heliophysics package with this template? [Submit it to be a PyHC package](https://heliopython.org/docs/adding_a_project/)!

# vs
vs is a next generation python environment tool. Instead of simply managing what python environments exist, it seeks to understand your project and ensure you have the Python you're asking for.

Goals:
* Be able to install Python on any system, using any major packaging tool
* Integrate with established tools to understand desired Pythons
* Allow developers to use the tools they like while alleviating a pain point

Non-goals:
* Define project structure
* Manage dependencies or define lock formats

Integrations include:
* Dependency tools: Generic pyproject.toml, Poetry, pip-tools, pipenv, uv
* Python installation: uv, pyenv, brew, apt, dnfs, pacman, Windows, vs
* Project commands: just

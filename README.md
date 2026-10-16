## makery-bakery

<img src="https://raw.githubusercontent.com/salomepoulain/makery-bakery/main/makery-bakery.png" width="360" alt="makery-bakery">

> A modular kitchen for your project's development environment.

Every project has a part that ships to GitHub and a part that doesn't: local caches, folders that
should follow you between machines, and the setup you redo for every project of the same kind.
makery-bakery handles that second part. You hire Stations into a project with `bake first <name>`,
and each one sets up its own environment and brings its own commands.

It's three repos that work together:

| Repo | What it is |
|---|---|
| [makery-bakery](https://github.com/salomepoulain/makery-bakery) | `bake` itself and the Head Chef that hires, fires and cleans up after Stations |
| [makery-stations](https://github.com/salomepoulain/makery-stations) | The registry: every Station you can hire (claude, python, github, latex, vault, ...) |
| [makery-kitchen-explorer](https://github.com/salomepoulain/makery-kitchen-explorer) | A VS Code extension that shows the kitchen in the Explorer: ignored files grey, germs almost invisible |

# Information for Ukrainians in Cyprus
This repository contains information for Ukrainians in Cyprus. It is a work in progress and will be updated regularly.
Contributions are welcome to all sections of the repository, including:
- Wiki;
- Discussion;
- Source code (pull-requests/issues with change requests).

[Українська версія цього README.md](README.UK.md)

## Building the site
The site is built using [Zensical](https://zensical.org/). To build the site locally, you need to have [Python](https://www.python.org/downloads/) installed,
preferably with [uv](https://docs.astral.sh/uv/), since it's used for locking the dependencies. (Alternatievly - you can run the [Devcontainer](https://containers.dev/) provided in this repository with your code editor)

### 1. Install dependencies
Simply running:
```bash
uv sync
```
Should sync up your dependencies with the `uv.lock` file.

### 2. Build the site
To build the site, run:
```bash
uv run zensical build
```

### 3. Debugging the site
To debug the site, run:
```bash
uv run zensical serve
```
This should start a local server negating a need for you to serve the static files manually.
Follow the terminal output to see the URL where the site is being served.

## Final notes
Licensed under [CC BY-SA-4.0](https://creativecommons.org/licenses/by-sa/4.0/), see LICENSE for details.

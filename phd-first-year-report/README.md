# First year PhD LaTeX report

Report of the activities during my first year of PhD.

It uses my LaTeX template using [mise](https://mise.jdx.dev/) and Visual Studio Code.

## Quick start

### MISE installation

Install MISE by following the guide [here](https://mise.jdx.dev/installing-mise.html). The simplest way is

```bash
curl https://mise.run | sh
```

### Setup latex environment

First trust the mise.toml by running

```bash
mise trust
```

Then proceed to install any packages needed via `tlmgr install [package]` or by adding the package to the `tex-packages.txt` file.

After `tlmgr install [package]` it's possible to save the requirements file via `mise run save-tex-packages`. It's also possible to install from a requirements file via `mise run install-tex-packages`.

### Build

To build the project just run
```bash
mise run build
```

To clean run
```bash
mise run clean
```

### VSCode setup

Most of the VSCode settings require the installation of the recommended extensions in `.vscode/extensions.json`.


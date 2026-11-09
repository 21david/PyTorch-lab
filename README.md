# PyTorch Lab

A repository for learning PyTorch through simple projects that gradually become more complex.

## Setup

This project uses [uv](https://docs.astral.sh/uv/) to manage Python and dependencies, and the [GitHub CLI](https://cli.github.com/) to work with GitHub from the command line.

It uses Python 3.12 and PyTorch 2.2.2 for compatibility with my Intel-based MacBook. PyTorch 2.2.x was the last release series with official support for Intel Macs.

To run the notebooks on your computer:

1. Install [Git](https://git-scm.com/install/) and [uv](https://docs.astral.sh/uv/getting-started/installation/).
2. Clone the repository and enter its folder:

   ```bash
   git clone https://github.com/21david/PyTorch-lab.git
   cd PyTorch-lab
   ```

3. Set up the environment and start JupyterLab:

   ```bash
   uv sync
   uv run jupyter lab
   ```

   `uv sync` creates the project's virtual environment and installs its dependencies from `uv.lock`. `uv run jupyter lab` starts JupyterLab using that environment. Open a notebook in JupyterLab and run its cells.

# replicate neuron density plots
We are at the hackday of the [Open Software Week ](https://neuroinformatics.dev/open-software-week/) of the Neuroinformatics Unit (NIU), based at the Sainsbury Wellcome Centre.  In this project we want to reproduce the plots density of neurons from an earlier paper.

## How to get started

These are the original paper, repo and data:
https://github.com/arberlab-wyhk/Yang-et-al-2022/tree/main
https://zenodo.org/records/7363150
https://www.cell.com/cell/fulltext/S0092-8674%2822%2901522-7

To get started with this project:
1. You need to install [UV](https://docs.astral.sh/uv/getting-started/installation/)
1. Clone the repo and go into the folder
1. Download the [data](https://zenodo.org/records/7363150)
1. Create a folder called 'DATA' in the root of the project and unpack all the data into that folder.
1. Follow the [UV instructions](https://docs.astral.sh/uv/pip/environments/) to create the environment (make sure that the dev dependencies from the `pyproject.toml` are also installed )
(1. if you use VScode, install the plugins that VSCode prompts you to install)
1. Now the cells in the notebook should run, if that enviroment is active


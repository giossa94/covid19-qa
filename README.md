# COVID-19 QA

## Installation

1. Setup the env. Install Miniconda (Linux setup; check online for MacOS and Windows):

    ```bash
    wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
    bash -b Miniconda3-latest-Linux-x86_64.sh
    ```

2. Open a new terminal after the installation.

    ```bash
    conda env create -f environment.yml
    conda activate covid19-qa
    ```

3. Download [the model](https://drive.google.com/drive/folders/1K-eXgmXytoIELHI8Rq3_dP9BUujBQ9T2?usp=sharing) in `model/`.

## Run

```bash
./scripts/main.py
```

## Elastic Search

### With Docker & DockerCompose

### With Docker

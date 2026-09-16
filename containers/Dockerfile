FROM condaforge/mambaforge:latest

LABEL maintainer="Adrian Aguilera Martin"

WORKDIR /workflow

COPY environment.yml /workflow/environment.yml
RUN mamba env create -f /workflow/environment.yml && mamba clean -afy

SHELL ["conda", "run", "-n", "pdac-er-immune-atlas", "/bin/bash", "-c"]

ENTRYPOINT ["conda", "run", "-n", "pdac-er-immune-atlas"]

# Non-accredited bioinformatic analyses

## Introduction

This repository contains documentation for the non-accredited bioinformatic analysis pipelines run at NGI Stockholm. Although these methods are more flexible than accredited ones, the aim is to be as specific as possible. E.g., to list current software versions, sequencing platforms currently support and which reference genomes we support.

## Structure

```
docs
|-- rnaseq                      # Pipeline 1
|   |-- images                  # Pipeline specific plots
|   |   |-- alignment.png
|   |   `-- qc_heatmap.svg
|   |-- supplementary           # Optional extras
|   |   |-- edge_cases.md       # Less structured notes
|   |   `-- external_comparisons_2025.pdf
|   `-- index.md               # Main doc
|-- smrnaseq                    # Pipeline 2
|   `-- index.md
|-- mkdocs.yml
`-- README.md

```

## Mkdocs

To build or serve this documentation locally, ensure you have MkDocs installed. You can install it using pip:

```bash
pip install mkdocs
```

Once installed, navigate to the repository's root directory and run:

```bash
mkdocs serve
```

This will start a local development server, and you can view the documentation in your browser at `http://127.0.0.1:8000/`. To build the static site, use:

```bash
mkdocs build
```

The generated static files will be placed in the `site` directory.

## Links

* [smrnaseq](docs/smrnaseq/index.md)


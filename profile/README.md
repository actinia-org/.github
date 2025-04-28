# Overview of actinia geoprocessing platform in the cloud

Software [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.5879231.svg)](https://doi.org/10.5281/zenodo.5879231)
Article [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.2631917.svg)](https://doi.org/10.5281/zenodo.2631917)
[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Docker pulls](https://img.shields.io/docker/pulls/mundialis/actinia-core.svg)](https://hub.docker.com/r/mundialis/actinia-core)

## Overview

Actinia is an open source REST API for scalable, distributed, high-performance
processing of geographical data that uses mainly GRASS GIS for computational
tasks (DOI: [10.5281/zenodo.5879231](https://doi.org/10.5281/zenodo.5879231)).

The actinia related repositories are organized as follows:

### 🌐 Core & API Repositories

- **[actinia-core](https://github.com/actinia-org/actinia-core):** Core REST API for geospatial processing.
- **[actinia-api](https://github.com/actinia-org/actinia-api):** API descriptions for actinia-core and official plugins.
  - **[actinia-api-documentation](https://redocly.github.io/redoc/?url=https://actinia.mundialis.de/latest/swagger.json&nocors):** Rendered API documentation.
- **[actinia-python-client](https://github.com/actinia-org/actinia-python-client):** Python client library for the actinia API.

### 🔌 Plugin Repositories

- **[actinia-parallel-plugin](https://github.com/actinia-org/actinia-parallel-plugin):** Parallel processing plugin.
- **[actinia-satellite-plugin](https://github.com/actinia-org/actinia-satellite-plugin):** Efficient satellite data handling plugin.
- **[actinia-stac-plugin](https://github.com/actinia-org/actinia-stac-plugin):** Interact with STAC catalogs.
- **[actinia-statistic-plugin](https://github.com/actinia-org/actinia-statistic-plugin):** Compute raster and time-series statistics.
- **[actinia-tiling-plugin](https://github.com/actinia-org/actinia-tiling-plugin):** Data tiling plugin.

### 🐳 Docker & Deployment

- **[actinia-docker](https://github.com/actinia-org/actinia-docker):** Docker configurations for actinia-core.
  - **[Docker images](https://hub.docker.com/r/mundialis/actinia-core):** Docker images of actinia-core.
- **[helm-charts](https://github.com/actinia-org/helm-charts):** Helm charts for Kubernetes deployment.

### 📝 Tutorials & Examples

- **[actinia-example-plugin](https://github.com/actinia-org/actinia-example-plugin):** Example plugin.
- **[actinia-introduction](https://github.com/actinia-org/actinia-introduction):** Introduction to actinia.
  - **[actinia tutorial](https://actinia-org.github.io/actinia-core/):** Rendered actinia tutorial.
- **[actinia-jupyter](https://github.com/actinia-org/actinia-jupyter):** Jupyter notebooks for tutorials.
- **[processing-examples](https://github.com/actinia-org/processing-examples):** Examples of processing chains.
- **[actinia slides](https://github.com/actinia-org/slides):** Slides about actinia.
  - **Presentation: [GRASS GIS in the cloud: actinia geoprocessing](https://htmlpreview.github.io/?https://github.com/actinia-org/slides/blob/main/intro/index.html):** (requires Chrome browser).

### 📚 Metadata & Infrastructure

- **[actinia-metadata-plugin](https://github.com/actinia-org/actinia-metadata-plugin):** Integration with metadata catalogs (GeoNetwork).
- **[actinia-gdi](https://github.com/actinia-org/actinia-gdi):** Integration with Spatial Data Infrastructure.

### 🌈 Contribution guidelines - how to get involved?

- Please see **[CONTRIBUTING](https://github.com/actinia-org/actinia-core/blob/main/CONTRIBUTING.md)**

### ♾️ Misc

- **[actinia-org.github.io](https://github.com/actinia-org/actinia-org.github.io):** Landing page for actinia-org
- **[Core maintainer actinia page at mundialis](https://actinia.mundialis.de/)**

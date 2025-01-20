# HMPPS Electronic Moniotring Create An Order(CEMO) Documentation Site

## About this project

This repository is used to generate the [technical documentation website](https://ministryofjustice.github.io/hmpps-integration-api-docs) for the [HMPPS Electronic Moniotring Create An Orde ](https://github.com/ministryofjustice/hmpps-electronic-monitoring-create-an-order) service.


## Requirements

- [Docker](https://www.docker.com/get-started/)
- [Ruby](https://github.com/rbenv/rbenv)

## Previewing locally

To run the application for local development:

```bash
make preview
```

Then visit http://localhost:4567.



## Checking links locally
### Running checks

To check the application compiles and URLs are valid:

```bash
make link-check
```

# Publishing

This template includes a GitHub Actions workflow ([`.github/workflows/publish.yml`](.github/workflows/publish.yml)) for publishing to GitHub Pages when merging to `main`.

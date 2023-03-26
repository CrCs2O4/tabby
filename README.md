## 🐾 Tabby
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
![Docker build status](https://img.shields.io/github/actions/workflow/status/TabbyML/tabby/docker.yml?label=docker%20image%20build)

> **Warning**
> This repository is undering heavy construction, everything changes fast.

An opensource / on-prem alternative to GitHub Copilot

## Development

Assuming Linux workstation with:
1. docker
2. docker w/ gpu driver
3. python 3.10

Use `make setup-development-environment` to setup basic dev environment, and `make dev` to start local development server.

## Deployment
1. `make up-triton`
2. Open Admin Panel [http://localhost:8501](http://localhost:8501)
3. Types some code in editor!

![Screenshot from 2023-03-25 21-31-24](https://user-images.githubusercontent.com/388154/227720212-7e7480a1-abb1-4baf-b971-d391ea8136c8.png)

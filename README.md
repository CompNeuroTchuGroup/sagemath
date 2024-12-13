# SageMath in Docker

This is a simple repository to quickly spin up a [SageMath](http://www.sagemath.org/) instance using Docker.

## Prerequisites

You need to have Docker installed on your system. You can download it from [here](https://www.docker.com/get-started).

## Usage

To start the server, simply run the following command in your terminal from the root of this repository:

```bash
docker compose up
```

Append the flag `-d` to run in the background:

```bash
docker compose up -d
```
# pycon-ireland-2025

## End-to-end testing with Testcontainers and Playwright

This repo was created to be used as an example during my talk at PyCon Ireland 2025, where I talked about how to get started with end-to-end tests using the popular libraries [Testcontainers]() and [Playwright]().

## Getting started

This project requires [Docker]() and [Poetry](). Get them through your favourite package manager before attempting to start the applications in this repo.

This project contains 4 modules:
- `core-api`, a basic backend service written in Python using [FastAPI]()
- `user-api`, a Python backend service using [FastAPI]() that exposes an API and communicates with `core-api` through [Kafka]()
- `user-admin`, a TypeScript app using [React Router]() in framework-mode, where the server performs server-side-rendering of pages while providing an API for the client to interact with.
- `e2e`, a Python module with a test suite using Playwright for end-to-end testing the other applications.

Refer to the READMEs in modules on how to start each application.

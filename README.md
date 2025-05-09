# Projects API Description

This repository contains the OpenAPI documentation for the Projects API of Mairie360.

It uses [Redocly CLI](https://redocly.com/docs/cli/) to bundle, preview, and build the API documentation.

## View the API Documentation

Go to the [Projects API Description](https://mairie360.github.io/projects-api-description) to view the live API documentation.

## Requirements

- Node.js (>=18.x recommended)
- npm

## Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/mairie360/projects-api-description.git
cd projects-api-description
npm install
```

## Usage

### Lint the OpenAPI file

```bash
npm run lint
```

### Build the bundled OpenAPI file

```bash
npm run build
```

Generates `build/openapi.yaml` from `src/openapi.yaml`.

---

### Build the documentation site (HTML)

```bash
npm run build-docs
```

Generates `build/index.html`, a static website with your API documentation.

---

### Preview the documentation locally

```bash
npm run preview
```

Opens a local server to view your documentation live.

## Folder Structure

```txt
src/
    parameters/
        # Parameter definitions
    resources/
        # Resource definitions
    responses/
        # Response definitions
    schemas/
        # Schema definitions
    security_schemes/
        # Security scheme definitions
    openapi.yaml   # Main OpenAPI file
build/
  openapi.yaml   # Bundled OpenAPI file
  index.html     # Generated documentation site
```

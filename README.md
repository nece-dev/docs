# OnePanel Mintlify documentation

This directory is the Mintlify documentation source for OnePanel.

## Preview locally

Install the Mintlify CLI, then run:

```sh
cd docs
mint dev
```

Validate the OpenAPI file with:

```sh
mint openapi-check openapi.yaml
```

Connect the repository (or this directory as the docs root) in the Mintlify dashboard to publish it. The current in-app `/api-docs` page can remain as a lightweight fallback until the Mintlify URL is available; once that URL is known, the dashboard link can point to it directly.

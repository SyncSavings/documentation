# Public website

[https://syncsavings.github.io/api-contract/](https://syncsavings.github.io/api-contract/)

We use [redocly](https://redocly.com/docs) to generate our documentation, `docs/main.yaml` and the files that it references follow the OpenAPI specification version 3.0.3

# Run locally

```sh
$ npm run build:dev
$ open http://127.0.0.1:8080/
```

# Publishing changes

Changes merged to `main` are built and deployed using GitHub Actions




# Mitu API documentation

The developer documentation for the Mitu platform, published with
[Fern](https://buildwithfern.com).

## Layout

    fern/
      docs.yml          navigation, theme, tabs
      styles.css        theme values taken from the Mitu design artboards
      openapi.yaml      the API reference source
      docs/pages/       one MDX file per page
      docs/assets/      logo and favicon

## Working on it

Install the CLI once:

    npm install -g fern-api

Preview locally:

    fern docs dev

Publish:

    fern generate --docs

Pull requests get a preview build automatically; merges to `main` publish.

## Navigation

The four tabs — Get started, Guides, Platform, API reference — and every section
under them come from the `Mitu API Docs` design artboards. Add a page by
creating the MDX file under `fern/docs/pages/` and adding it to `docs.yml`; a
page that is not in `docs.yml` is not published.

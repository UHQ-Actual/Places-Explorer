# Places Crosswalk Explorer

This public repository is the deployment shell for the
[Places Crosswalk Explorer](https://uhq-actual.github.io/Places-Explorer/).

The source workbooks, UI, and deterministic data builder remain in the private
`UHQ-Actual/Places` repository. A GitHub Actions workflow checks out that source
with a read-only repository secret, builds the static search shards, and uploads
only the generated website to GitHub Pages. No source workbook or API credential
is committed here.

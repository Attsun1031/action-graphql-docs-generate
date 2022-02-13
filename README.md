# action-graphql-docs-generate
A github action that generate graphql API documents.

Currently, we use [spectaql](https://github.com/anvilco/spectaql) generate docs.

# How to use
Embed in your github action yaml.

```yaml
      - name: Generate GraphQL docs
        uses: Attsun1031/action-graphql-docs-generate@v0.1.0
        with:
          spectaql-config-path: "path/to/spectaql-configuration"
          output-dir: "path/to/document-output-dir"
```


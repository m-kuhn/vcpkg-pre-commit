# vcpkg-pre-commit

A [pre-commit](https://pre-commit.com/) hook for [vcpkg](https://github.com/microsoft/vcpkg).

### Using vcpkg format with pre-commit

To use vcpkg format-manifest via pre-commit, add the following to your `.pre-commit-config.yaml`:

```yaml
- repo: https://github.com/m-kuhn/vcpkg-pre-commit
  rev: v0.1.0
  hooks:
    # Run the formatter.
    - id: vcpkg-format
```


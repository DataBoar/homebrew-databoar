# Homebrew tap for Data Boar

**Not [homebrew-core](https://github.com/Homebrew/homebrew-core).** This is Data Boar’s own tap.

```bash
brew tap DataBoar/databoar
brew install data-boar
data-boar --demo
```

The formula uses Homebrew’s Python and pip-installs the PyPI package. It does **not** embed CPython.

Canonical formula and bump automation live in the product repo:

- [DataBoar/data-boar](https://github.com/DataBoar/data-boar) — `packaging/homebrew/Formula/data-boar.rb`
- Operator notes: [HOMEBREW_TAP.md](https://github.com/DataBoar/data-boar/blob/main/docs/ops/HOMEBREW_TAP.md)

Issue: [#1425](https://github.com/DataBoar/data-boar/issues/1425)

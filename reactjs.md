# pre-commit reactjs

```
repos:
-   repo: https://github.com/pre-commit/pre-commit-hooks
    rev: v2.3.0
    hooks:
    -   id: end-of-file-fixer #end-of-file-fixer - ensures that a file is either empty, or ends with one newline.
    -   id: trailing-whitespace #trailing-whitespace - trims trailing whitespace.
-   repo: https://github.com/pre-commit/mirrors-eslint
    rev: 'v8.16.0'
    hooks:
    -   id: eslint #github.com/pre-commit/mirrors-eslint
```

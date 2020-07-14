This repo contains a [pre-commit](https://pre-commit.com/) hook for [yasi](https://pypi.org/project/yasi/).

## Usage

In your .pre-commit-config.yaml:

```yaml
- repo: https://github.com/arenadotio/pre-commit-yasi
  rev: master # or pick a commit sha I guess
  hooks:
    - id: yasi
      files: # insert your regex here
```

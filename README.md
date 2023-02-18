project-partials
===

Partial files for projects to copy&pasta and adjust

## Partials

### Contribution guidelines

#### Contribution guidelines for projects using CircleCI

- [Template](./partials/CONTRIBUTING.circleci.md)
- Templating:
  ```bash
  export PROJECT_NAME=Human project name
  export LICENSE_NAME=license name
  export REPO_SLUG_NAME=repo-name-github
  curl -sS https://raw.githubusercontent.com/timo-reymann/project-partials/main/partials/CONTRIBUTING.circleci.md | envsubst
  ```


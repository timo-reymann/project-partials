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

### READMEs

#### README with Circleci or GitHub Workflow

- [Template](./partials/README.general.md)
- Templating:
  ```bash
  export PROJECT_NAME=Human project name
  export REPO_SLUG_NAME=repo-name-github
  curl -sS https://raw.githubusercontent.com/timo-reymann/project-partials/main/partials/README.general.md | envsubst
  ```

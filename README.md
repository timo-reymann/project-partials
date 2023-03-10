project-partials
===
[![LICENSE](https://img.shields.io/github/license/timo-reymann/project-partials)](https://github.com/timo-reymann/project-partials/blob/main/LICENSE)


<p align="center">
	<img width="300" src=".github/images/logo.png">
    <br />
    Partial files for projects to copy&pasta and adjust
</p>

## Usage

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
#### Contribution guidelines for projects using GitHub Actions
- [Template](./partials/CONTRIBUTING.github-actions.md)
- Templating:
  ```bash
  export PROJECT_NAME=Human project name
  export LICENSE_NAME=license name
  export REPO_SLUG_NAME=repo-name-github
  curl -sS https://raw.githubusercontent.com/timo-reymann/project-partials/main/partials/CONTRIBUTING.github-actions.md | envsubst
  ```

#### Contribution guidelines for projects using no pipeline
- [Template](./partials/CONTRIBUTING.no-pipeline.md)
- Templating:
  ```bash
  export PROJECT_NAME=Human project name
  export LICENSE_NAME=license name
  export REPO_SLUG_NAME=repo-name-github
  curl -sS https://raw.githubusercontent.com/timo-reymann/project-partials/main/partials/CONTRIBUTING.no-pipeline.md | envsubst
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

#### README for GitHub Action
- [Template](./partials/README.github-action.md)
- Templating:
  ```bash
  export PROJECT_NAME=my-action
  curl -sS https://raw.githubusercontent.com/timo-reymann/project-partials/main/partials/README.github-action.md | envsubst
  ```
#### README for Slides
- [Template](./partials/README.slides.md)
- Templating:
  ```bash
  export PROJECT_NAME=my-action
  curl -sS https://raw.githubusercontent.com/timo-reymann/project-partials/main/partials/README.slides.md | envsubst
  ```

#### README for Homebrew formulas
- [Template](./partials/README.homebrew.md)
- Templating:
  ```bash
  export PROJECT_NAME=my-source-project
  curl -sS https://raw.githubusercontent.com/timo-reymann/project-partials/main/partials/README.homebrew.md | envsubst
  ```

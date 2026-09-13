# discourse

> A platform for community discussion. Free, open, simple.

---

## Table of Contents

1. [Overview](#overview)
2. [Tech Stack](#tech-stack)
3. [Repository Structure](#repository-structure)
4. [Key Components](#key-components)
5. [Setup & Installation](#setup--installation)
6. [Running the Application](#running-the-application)
7. [Infrastructure & CI/CD](#infrastructure--cicd)
8. [Contributing](#contributing)

---

## Overview

**discourse** is part of the [Unacademy](https://github.com/unacademy) engineering ecosystem.

A platform for community discussion. Free, open, simple.

**Topics / Tags:** _None_

---

## Tech Stack

| Attribute | Value |
|-----------|-------|
| **Primary Language** | Unknown |
| **Framework / Platform** | Django |
| **Package Manager** | — |

### Dependencies

**Runtime Dependencies:**
- `@discourse/itsatrap`
- `@fortawesome/fontawesome-free`
- `@discourse/moment-timezone-names-translations`
- `@highlightjs/cdn-assets`
- `@json-editor/json-editor`
- `@popperjs/core`
- `@uppy/aws-s3`
- `@uppy/aws-s3-multipart`
- `@uppy/core`
- `@uppy/drop-target`
- `@uppy/utils`
- `@uppy/xhr-upload`
- `ace-builds`
- `bootbox`
- `bootstrap`

**Dev Dependencies:**
- `@arkweid/lefthook`
- `@mixer/parallel-prettier`
- `browserify`
- `chrome-launcher`
- `chrome-remote-interface`
- `pretender`
- `puppeteer-core`
- `qunit`
- `route-recognizer`
- `sinon`


---

## Repository Structure

```
discourse/
├── .devcontainer
├── .editorconfig
├── .eslintignore
├── .eslintrc
├── .git-blame-ignore-revs
├── .gitattributes
├── .github/
│   ├── dependabot.yml
│   ├── pull_request_template.md
│   ├── workflows
├── .gitignore
├── .licensed.yml
├── .npmrc
├── .prettierignore
├── .prettierrc
├── .rspec
├── .rspec_parallel
├── .rubocop.yml
├── .ruby-gemset.sample
├── .ruby-version.sample
├── .template-lintrc.js
├── .vscode-sample/
│   ├── launch.json
│   ├── tasks.json
├── Brewfile
├── CONTRIBUTING.md
├── COPYRIGHT.md
├── Gemfile
├── Gemfile.lock
├── LICENSE.txt
├── README.md
├── Rakefile
... (truncated)
```

---

## Key Components

Below is an analysis of the key files and modules:

| File / Directory | Purpose |
|-----------------|---------|


> **Note:** Only the first 20 non-trivial files are listed. See the repository tree above for the complete structure.

---

## Setup & Installation

### Prerequisites

- Git (`git --version`)
- Unknown runtime installed



### Steps

```bash
# 1. Clone the repository
git clone git@github.com:unacademy/discourse.git
cd discourse

# 2. Install dependencies
npm install      # or yarn install
```

### Available Scripts

```bash
# postinstall
npm run postinstall   # yarn --cwd app/assets/javascripts/discourse

```


---

## Running the Application

_Refer to the project's build system or CI configuration._

---

## Infrastructure & CI/CD

- CI/CD pipeline configured (`.github/workflows` or equivalent)
- Test suite present — run tests before submitting PRs

---

## Contributing

1. Create a feature branch: `git checkout -b feat/your-feature`
2. Commit your changes: `git commit -m "feat: describe your change"`
3. Push and open a PR targeting `main`
4. Ensure all CI checks pass before requesting review

---

## Original README (Excerpt)

> <a href="https://www.discourse.org/">
  <img src="images/discourse-readme-logo.png" width="300px">
</a>

Discourse is the 100% open source discussion platform built for the next decade of the Internet. Use it as a:

- mailing list
- discussion forum
- long-form chat room

To learn more about the philosophy and goals of the project, [visit **discourse.org**](https://www.discourse.org).

## Screenshots

 
<a href="https://bbs.boingboing.net"><img alt="Boing Boing" src="https://user-images.githubusercontent.com/1681963/52239245-04ad8280-289c-11e9-9c88-8c173d4a0422.png" width="720px"></a>
<a href=

---

*This README was auto-generated on 2026-09-14 by the Unacademy repo-summarizer tool.*
*For corrections or additions, edit this file directly or open an issue.*

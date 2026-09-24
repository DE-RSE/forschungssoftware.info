---
title: "Issue2Docker"
groupByYear: false
showDate: false
hero: true
draft: false
series: ["FSI services"]
showSummary: true
#Summary is shown on the overview page of services
summary: "Issue2Docker allows building reproducible environments from GitHub issues and discussions."
authors:
  - "camilla.luettgens"
  - "zhenlu.ren"
---

## Target audience

Maintainers and users of research software, who work with GitHub issues.

## Service description
> [Issue2Docker](https://gitlab.git.nrw/rpdm/projects-and-services/caesar/issue2docker) allows building reproducible environments from GitHub issues and discussions as part of the [CAES³AR](../../projects/caesar) workflow. It is a Python command-line tool that can be tried out on our [testpage](https://caesar-testpage.tools.web.gateway.ionos.coscine.dev/).
> The tool transforms the issue/discussion markdown into a Jupyter Notebook, extracts attachments such as data files, creates environment configuration files, and stores the issue artifact in GitHub. The outputs are links to build the environments directly with [mybinder.org](https://mybinder.org/) or [Jupyter4NFDI](https://nfdi-jupyter.de/), or a command to build the environment with [Repo2Docker](https://repo2docker.readthedocs.io/).

## Status

in active development with a first test-version released

## Participating projects

[CAES³AR](../../projects/caes3ar)
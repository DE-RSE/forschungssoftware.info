---
title: "Issue2Docker"
groupByYear: false
showDate: false
hero: true
draft: false
series: ["FSI services"]
showSummary: true
#Summary is shown on the overview page of services
summary: "Issue2Docker ermöglicht es, reproduzierbare Umgebungen aus GitHub Issues und Diskussionen zu erzeugen."
authors:
  - "camilla.luettgens"
  - "zhenlu.ren"
---

## Zielgruppe

Entwickelnde und Nutzende von Forschungssoftware, die mit GitHub Issues arbeiten.

## Servicebeschreibung
> [Issue2Docker](https://gitlab.git.nrw/rpdm/projects-and-services/caesar/issue2docker) ermöglicht es, reproduzierbare Umgebungen aus GitHub Issues und Diskussionen zu erzeugen und ist Teil des [CAES³AR](../../projects/caesar) Worflows. Es ist ein Python Kommandozeilentool, das auf unserer [Testseite](https://caesar-testpage.tools.web.gateway.ionos.coscine.dev/) ausprobiert werden kann.
> Das Tool konvertiert das Markdown von Issues/Diskussionen in ein Jupyter Notebook, extrahiert Anhänge wie Datendateien, erzeugt Umgebungskonfigurationsdateien, und speichert das Issue Artefakt in GitHub. Der Output besteht aus Links um die Umbegung direkt mit [mybinder.org](https://mybinder.org/) oder [Jupyter4NFDI](https://nfdi-jupyter.de/) zu öffnen, oder das Kommando um die Umbegung mit [Repo2Docker](https://repo2docker.readthedocs.io/) zu bauen.

## Status

in Entwicklung mit einer ersten Testversion

## Beteiligte Projekte

[CAES³AR](../../projects/caes3ar)
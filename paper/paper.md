---
title: 'BH25DE report: On the path to machine-actionable training materials'
title_short: 'BH25DE: machine-actionable training'
tags:
- training
- learning resource
- metadata schema
- learning path
- LLMs
- metadata exchange
authors:
  - name: Phil Reed
    orcid: 0000-0002-4479-715X
    affiliation: 1
    role: Writing – original draft, Software
  - name: Nick Juty
    orcid: 0000-0002-2036-8350
    affiliation: 1
    role: Conceptualization, Writing – review & editing
  - name: Petra Steiner
    orcid: 0000-0001-8997-2620
    affiliation: 2
    role: Conceptualization, Writing – review & editing
  - name: Leyla Jael Castro
    orcid: 0000-0003-3986-0510
    affiliation: 3
    role: Methodology, Software, Writing - review & editing
  - name: Charles Tapley Hoyt
    orcid: 0000-0003-4423-4370
    affiliation: 4
    role: Methodology, Software, Writing - review & editing
  - name: Oliver Knodel
    orcid: 0000-0001-8174-7795
    affiliation: 5
    role: Methodology, Writing - review & editing
  - name: Martin Voigt
    orcid: 0000-0001-5556-838X
    affiliation: 5
    role: Software, Writing - review & editing
  - name: Roman Baum
    orcid: 0000-0001-5246-9351
    affiliation: 6
    role: Software, Writing - review & editing
  - name: Dilfuza Djamalova
    orcid: 0009-0004-7782-2894
    affiliation: 7
    role: Software, Writing - review & editing
  - name: Jacobo Miranda
    orcid: 0009-0005-0673-021X
    affiliation: 8
    role: Methodology, Writing - review & editing
  - name: Alban Gaignard
    orcid: 0000-0002-3597-8557
    affiliation: 8
    role: Methodology, Software
affiliations:
  - name: The University of Manchester
    ror: 027m9bs27
    index: 1
  - name: Technical University of Darmstadt
    ror: 05n911h24
    index: 2
  - name: ZB MED
    ror: 0259fwx54
    index: 3
  - name: RWTH Aachen University
    ror: 04xfq0f34
    index: 4
  - name: Helmholtz-Zentrum Dresden-Rossendorf
    ror: 01zy2cs03
    index: 5
  - name: University of Bonn
    ror: 041nas322
    index: 6
  - name: Forschungszentrum Jülich
    ror: 02nv7yv05
    index: 7
  - name: European Molecular Biology Laboratory
    ror: 03mstc592
    index: 8
  - name: University of Nantes
    ror: 03gnr7b55
    index: 9
date: 5 December 2025
cito-bibliography: paper.bib
event: BH25DE
biohackathon_name: "4th BioHackathon Germany"
biohackathon_url: "https://www.denbi.de/de-nbi-events/1840-4th-biohackathon-germany"
biohackathon_location: "Walsrode, Germany"
group: Project 10
# URL to project git repo --- should contain the actual paper.md:
git_url: https://github.com/PhilReedData/bhde-training-schema-report
# This is the short authors description that is used at the
# bottom of the generated paper (typically the first two authors):
authors_short: First Author \emph{et al.}
---


# Introduction

As part of the 4th BioHackathon Germany, we here report...


# Formatting

This document use Markdown and you can look at [this tutorial](https://www.markdowntutorial.com/).

## Subsection level 2

Please keep sections to a maximum of only two levels.

## Tables

Tables can be added in the following way, though alternatives are possible:

```markdown
Table: Note that table caption is automatically numbered and should be
given before the table itself.

| Header 1 | Header 2 |
| -------- | -------- |
| item 1 | item 2 |
| item 3 | item 4 |
```

This gives:

Table: Note that table caption is automatically numbered and should be
given before the table itself.

| Header 1 | Header 2 |
| -------- | -------- |
| item 1 | item 2 |
| item 3 | item 4 |

## Figures

A figure is added with:

```markdown
![Caption for BioHackrXiv logo figure](./biohackrxiv.png)
```

This gives:

![Caption for BioHackrXiv logo figure](./biohackrxiv.png)

Figures can be scaled by adding the width or height to the Markdown like this:

```markdown
![Caption for BioHackrXiv logo figure](./biohackrxiv.png){ width=50px }
```

# Other main section on your manuscript level 1

Lists can be added with:

1. Item 1
2. Item 2

# Citation Typing Ontology annotation

You can use [CiTO](http://purl.org/spar/cito/2018-02-12) annotations, as explained in [this BioHackathon Europe 2021 write up](https://raw.githubusercontent.com/biohackrxiv/bhxiv-metadata/main/doc/elixir_biohackathon2021/paper.md) and [this CiTO Pilot](https://www.biomedcentral.com/collections/cito).
Using this template, you can cite an article and indicate _why_ you cite that article, for instance DisGeNET-RDF [@citesAsAuthority:Queralt2016].

The syntax in Markdown is as follows: a single intention annotation looks like
`[@usesMethodIn:Krewinkel2017]`; two or more intentions are separated
with colons, like `[@extends:discusses:Nielsen2017Scholia]`. When you cite two
different articles, you use this syntax: `[@citesAsDataSource:Ammar2022ETL; @citesAsDataSource:Arend2022BioHackEU22]`.

Possible CiTO typing annotation include:

* citesAsDataSource: when you point the reader to a source of data which may explain a claim
* usesDataFrom: when you reuse somehow (and elaborate on) the data in the cited entity
* usesMethodIn
* citesAsAuthority
* citesAsEvidence
* citesAsPotentialSolution
* citesAsRecommendedReading
* citesAsRelated
* citesAsSourceDocument
* citesForInformation
* confirms
* documents
* providesDataFor
* obtainsSupportFrom
* discusses
* extends
* agreesWith
* disagreesWith
* updates
* citation: generic citation


# Results


# Discussion

...

## Acknowledgements

...

## References

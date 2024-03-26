---
layout: ontology_detail
id: ODKTestUpdateRepo
title: ODK1.5 test update repo
jobs:
  - id: https://travis-ci.org/pfabry/ODKTestUpdateRepo
    type: travis-ci
build:
  checkout: git clone https://github.com/pfabry/ODKTestUpdateRepo.git
  system: git
  path: "."
contact:
  email: 
  label: 
  github: 
description: ODK1.5 test update repo is an ontology...
domain: stuff
homepage: https://github.com/pfabry/ODKTestUpdateRepo
products:
  - id: ODKTestUpdateRepo.owl
    name: "ODK1.5 test update repo main release in OWL format"
  - id: ODKTestUpdateRepo.obo
    name: "ODK1.5 test update repo additional release in OBO format"
  - id: ODKTestUpdateRepo.json
    name: "ODK1.5 test update repo additional release in OBOJSon format"
  - id: ODKTestUpdateRepo/ODKTestUpdateRepo-base.owl
    name: "ODK1.5 test update repo main release in OWL format"
  - id: ODKTestUpdateRepo/ODKTestUpdateRepo-base.obo
    name: "ODK1.5 test update repo additional release in OBO format"
  - id: ODKTestUpdateRepo/ODKTestUpdateRepo-base.json
    name: "ODK1.5 test update repo additional release in OBOJSon format"
dependencies:
- id: bfo
- id: obi

tracker: https://github.com/pfabry/ODKTestUpdateRepo/issues
license:
  url: http://creativecommons.org/licenses/by/3.0/
  label: CC-BY
activity_status: active
---

Enter a detailed description of your ontology here. You can use arbitrary markdown and HTML.
You can also embed images too.


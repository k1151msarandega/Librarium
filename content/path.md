---
title: 'Path'
date: 2026-11-01
type: landing

design:
  spacing: '5rem'

sections:
  - block: markdown
    content:
      title: A continuing record
      text: |-
        Every role, programme, credential and act of service, in date order. Select a thread tag on any entry to see everything connected to it.
    design:
      columns: '1'
  - block: content-collection
    content:
      title: Roles and research
      filters:
        folders: [record]
        category: Role
    design:
      view: path
  - block: content-collection
    content:
      title: Service and leadership
      filters:
        folders: [record]
        category: Service
    design:
      view: path
  - block: content-collection
    content:
      title: Programmes and credentials
      filters:
        folders: [record]
        category: Credential
    design:
      view: path
---

---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2026-11-01
type: landing

sections:
  - block: resume-biography-3
    content:
      # Author profile lives in data/authors/me.yaml
      username: me
      text: ''
      button:
        text: Connect on LinkedIn
        url: https://www.linkedin.com/in/kudzai-musarandega-5156a521a/
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  - block: markdown
    content:
      title: Right now
      subtitle: ''
      text: |-
        - **Product Development Engineer, QuantrolOx.** Writing foundations curriculum for a quantum engineering training programme.
        - **Quantum Solutions Research Fellow, WISER.** Building operator-level mappings between computational fluid dynamics and quantum computing.
        - **Independent research.** An autonomous, uncertainty-driven agent for tuning quantum-dot devices (in development).
        - **Lead Ambassador and Africa operations manager,** Diffie-Hellman Key Exchange 50th Anniversary, with the IEEE SSIT Sustainability Technical Committee.
    design:
      columns: '1'

  - block: focus-areas
    content:
      title: Four threads
      subtitle: Everything on this site is tagged to one or more of these.
      text: Select a thread to see every project, role and honour connected to it.
      items:
        - name: Devices
          description: Spintronic, optical and semiconductor hardware, from measurement and fabrication to integration.
          icon: hero/cpu-chip
          cta:
            text: Explore Devices
            url: /tags/devices/
        - name: Computation
          description: Quantum algorithms, machine learning, autonomous agents and immersive systems.
          icon: hero/beaker
          cta:
            text: Explore Computation
            url: /tags/computation/
        - name: Policy and Narrative
          description: Science and technology policy, branding and storytelling that put technical work in front of decision makers.
          icon: hero/document-text
          cta:
            text: Explore Policy and Narrative
            url: /tags/policy-and-narrative/
        - name: Teaching and Leadership
          description: Curriculum, tutoring, mentoring and the communities and committees that bring more people to the frontier.
          icon: hero/academic-cap
          cta:
            text: Explore Teaching and Leadership
            url: /tags/teaching-and-leadership/
    design:
      layout: cards

  - block: content-collection
    content:
      title: Selected work
      text: ''
      filters:
        folders:
          - projects
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: content-collection
    content:
      title: Recognition
      text: ''
      count: 6
      filters:
        folders:
          - record
        category: Award
        featured_only: true
    design:
      view: date-title-summary

  - block: focus-areas
    content:
      title: Trajectory
      subtitle: Four stages, each wider in scope and responsibility than the last.
      items:
        - name: Foundations (2017 to 2021)
          description: Top national results in Zimbabwe, a first research training programme in cybersecurity, and a Global Wildcat scholarship to study in the United States.
          icon: hero/sparkles
        - name: Apprenticeship (2021 to 2023)
          description: Industry externship, design-thinking consulting, physics tutoring and Supplemental Instruction, the Student Advisory Board, and a first machine-learning research role.
          icon: hero/sparkles
        - name: Independent contribution (2023 to 2025)
          description: Spintronics lab work, a peer-reviewed paper, two International Physicists' Tournaments, optical engineering, a statewide branding win and a BSc in Engineering Physics.
          icon: hero/sparkles
        - name: Leadership and authorship (2025 onward)
          description: Research fellowships, hackathon wins, curriculum authorship, a state space-policy fellowship and international organising roles.
          icon: hero/sparkles
          status: active
    design:
      layout: timeline
---

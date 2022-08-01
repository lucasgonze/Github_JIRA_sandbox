---
name: Bug report
about: Describe a scenario in which this project behaves unexpectedly
title: ''
labels: bug, needs-triage
assignees: ''
body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to fill out this bug report!
  - type: dropdown
    id: jira-status
    attributes:
      label: Jira Status
      description: (Internal)
      options:
        - Backlog
        - In Progress
        - Selected for Development
        - In Review 
        - In Staging
        - Blocked
        - Closed
    validations:
      required: false

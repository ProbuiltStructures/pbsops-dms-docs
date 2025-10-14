---
name: Access Request
about: Access Request
title: ''
labels: ''
assignees: ''

---

name: Access Request
description: Request access to the private PBS Ops repository
title: "Access Request: Your Name"
labels: ["access"]
body:
  - type: input
    id: github
    attributes:
      label: GitHub Username
      placeholder: "@yourusername"
    validations:
      required: true
  - type: input
    id: role
    attributes:
      label: Role / Scope
      placeholder: "e.g., Frontend developer (admin UI)"
    validations:
      required: true
  - type: textarea
    id: confirm
    attributes:
      label: Confirmation
      description: "Type: I have read CONTRIBUTING.md and will follow the workflow."
      placeholder: "I have read CONTRIBUTING.md and will follow the workflow."
    validations:
      required: true

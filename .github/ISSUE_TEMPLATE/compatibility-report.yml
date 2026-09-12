---
name: Compatibility Report
about: A template for reporting game compatibility
title: ''
labels: ''
assignees: ''

---

name: "Compatibility Report"
description: Report a game's compatibility.
title: "🐛 [REPORT] - <title>"
labels: [
  "report"
]
body:
  - type: input
    id: title
    attributes:
      label: "Name"
      description: What is the name of the game?
      placeholder: Game name...
    validations:
      required: true

  - type: input
    id: region
    attributes:
      label: "Region"
      description: Please enter the specific region of the game
      placeholder: ex. Japan, USA, Europe, World...
    validations:
      required: true

  - type: dropdown
    id: bios
    attributes:
      label: "BIOS"
      description: What BIOS did you test it on ?
      multiple: true
      options:
        - Open Source BIOS
        - Retail BIOS
    validations:
      required: false
  - type: dropdown
    id: condition
    attributes:
      label: "Condition"
      description: What is the game's condition?
      multiple: true
      options:
        - Broken
        - Boots to title
        - Playable with issues
        - Fully working
    validations:
      required: true

  - type: textarea
    id: description
    attributes:
      label: "Issues (if any)"
      description: Please describe any issues you encountered while testing
      placeholder: Any issues while testing...
    validations:
      required: true

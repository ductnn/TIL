---
name: 🐛 Bug Report
description: Report a reproducible bug
labels: ["type: bug"]
body:
  - type: input
    attributes:
      label: TIL version
      description: >
        What version of TIL are you currently running?
      placeholder: v1.0.0
    validations:
      required: true
  - type: dropdown
    attributes:
      label: Python version
      description: What version of Python are you currently running?
      options:
        - 3.7
        - 3.8
        - 3.9
    validations:
      required: true
  - type: textarea
    attributes:
      label: Expected Behavior
      description: What did you expect to happen?
      placeholder: A new widget should have been created with the specified attributes
    validations:
      required: true
  - type: textarea
    attributes:
      label: Observed Behavior
      description: What happened instead?
      placeholder: A TypeError exception was raised
    validations:
      required: true

---
name: Feature request
about: Request an enhancement for Vitistack
title: ''
labels: Request
body:

  - type: markdown
    attributes:
      value: |
        Before requesting: search [existing feature requests](https://github.com/vitistack/general/issues?q=state%3Aopen%20type%3ARequest).

  - type: textarea
    attributes:
      label: "Problem"
      description: "Describe the problem to be solved."
      placeholder: "No smurf icons available. Smurfs are useful because ..."
    validations:
      required: true

  - type: textarea
    attributes:
      label: "Expected behavior"
      description: "Describe what the new feature or behavior would look like. How does it solve the problem? Is it worth the cost?"
    validations:
      required: true
---

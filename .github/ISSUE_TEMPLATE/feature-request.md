name: Feature request
about: Request an enhancement for Vitistack
title: "[Feature request]: "
labels: Request
body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to fill out this report!
  - type: textarea
    attributes:
      label: Problem
      description: Describe the problem to be solved.
      placeholder: Tell us ...
    validations:
      required: true
  - type: textarea
    attributes:
      label: Expected behavior
      description: Describe what the new feature or behavior would look like. How does it solve the problem? Is it worth the cost?
      placeholder: Tell us ...
    validations:
      required: true

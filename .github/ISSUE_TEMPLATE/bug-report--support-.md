name: Proposal
description: Suggest an idea for this project
title: 'proposal: '
labels: proposal
assignees: peaceiris
body:
  - type: markdown
    attributes:
      value:
        Please note we will close your issue without comment if you do not fill out the issue checklist below and provide ALL the requested information.
  - type: checkboxes
    attributes:
      label: Checklist
      description: Checklist before creating an issue.
      options:
        - label: "I am using the latest version of this action."
          required: true
        - label: "I have read the latest README and followed the instructions."
          required: true
        - label: "I have read the latest GitHub Actions official documentation and learned the basic spec and concepts."
          required: true
  - type: textarea
    attributes:
      label: "Describe your proposal"
      description: "A clear and concise description of what the proposal is."
    validations:
      required: true
  - type: textarea
    attributes:
      label: "Describe the solution you'd like"
      description: "A clear and concise description of what you want to happen."
    validations:
      required: true
  - type: textarea
    attributes:

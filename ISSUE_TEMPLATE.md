name: C16AQ local preview
description: Request or report the local synthetic preview
body:
  - type: checkboxes
    id: consent
    attributes:
      label: Scope
      options:
        - label: I will not include private event data.
          required: true
  - type: textarea
    id: request
    attributes:
      label: Request
      description: What would you like to test or report?

---
name: Feature request
about: 새로운 기능 추가, 기존의 기능 개선을 요청하기 위한 템플릿입니다.
title: ''
labels: ''
assignees: ''
body:
  - type: input
    id: design_doc
    attributes:
      label: Design Doc
      description: Add a design doc if there is one for this feature.
  - type: textarea
    id: description
    attributes:
      label: Description
      description: Please describe the feature you are adding.
    validations:
      required: true
  - type: textarea
    id: tracking_issues
    attributes:
      label: Tracking Issues
      description: List of issues associated with this feature.
    validations:
      required: true

---

name: Feature request
description: 새로운 기능 추가, 기존의 기능 개선을 요청하기 위한 템플릿입니다.
body:
  - type: input
    id: design_doc
    attributes:
      label: 디자인 문서
      description: 이 기능을 위한 디자인 문서(링크)가 있다면 추가해주세요.
  - type: textarea
    id: description
    attributes:
      label: 기능 설명
      description: 추가할 기능에 대해 설명해주세요.
    validations:
      required: true
  - type: textarea
    id: tracking_issues
    attributes:
      label: 관련 이슈
      description: 이 기능과 관련된 이슈가 있다면 추가해주세요.

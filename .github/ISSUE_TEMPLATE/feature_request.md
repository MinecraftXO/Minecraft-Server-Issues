---
name: 💡 新功能反馈
about: 写下你想对服务器的新功能的描述
title: "[Feature]"
labels: enhancement
---
body:
  - type: markdown
    attributes:
      value: |
        感谢你的建议！请尽可能详细地描述。
  - type: textarea
    id: description
    attributes:
      label: 描述你的想法
      description: 你希望增加什么功能？它解决了什么问题？
      placeholder: 我希望增加...
    validations:
      required: true

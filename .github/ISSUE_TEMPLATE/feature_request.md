name: 💡 新功能建议
description: 为服务器提出一个新的玩法或功能建议
title: "[Feature]: "
labels: ["enhancement"]
body:
  - type: markdown
    attributes:
      value: |
        感谢你对服务器发展的关心！请详细描述你的想法。
  - type: textarea
    id: related-problem
    attributes:
      label: 你的建议是否与某个问题有关？
      description: 请简单描述一下现状。
    validations:
      required: false
  - type: textarea
    id: solution
    attributes:
      label: 描述你想要的解决方案
      description: 你希望增加什么插件？修改什么规则？越详细越好。
    validations:
      required: true

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
      description: 请简单描述一下现状（例如：现在的生存模式太无聊了...）。
    validations:
      required: false
  - type: textarea
    id: solution
    attributes:
      label: 描述你想要的解决方案
      description: 你希望增加什么插件？修改什么规则？或者增加什么新的游戏机制？越详细越好。
    validations:
      required: true
  - type: textarea
    id: alternatives
    attributes:
      label: 你考虑过其他的替代方案吗？
      description: 是否有其他方式可以实现类似的效果？
    validations:
      required: false
  - type: textarea
    id: additional-context
    attributes:
      label: 其他补充信息
      description: 如果有参考的截图、视频或其他服务器的例子，可以在这里提供。

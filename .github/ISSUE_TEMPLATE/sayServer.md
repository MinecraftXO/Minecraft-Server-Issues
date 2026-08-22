name:  讨论服务器
description: 说说服务器怎么样，分享你的想法或建议。
title: "[讨论]: "
labels: ["Say"]

body:
  - type: markdown
    attributes:
      value: |
        欢迎参与服务器讨论！为了让我们能更好地倾听你的声音，请认真填写以下内容。

  - type: textarea
    id: discussion_content
    attributes:
      label:  你想说什么？
      description: 请详细描述你对服务器的看法、建议或感受（请务必写点东西哦！）。
      placeholder: 比如："我感觉服务器XXX，希望以后可以XXX..."
    validations:
      required: true

  - type: input
    id: game_id
    attributes:
      label:  你的游戏ID
      description: 请填写你在服务器中的游戏ID。
      placeholder: 例如：Steve
    validations:
      required: true

  - type: input
    id: contact_info
    attributes:
      label:  我们怎样联系你？
      description: 最好提供电子邮箱，方便我们在有回复时通知你。
      placeholder: 例如：example@email.com
    validations:
      required: true


name: "综合 Bug 反馈"
description: "遇见了服务器的Bug"
labels: [· Bug, 新提交的漏洞]
body:
- type: checkboxes
  id: "yml-1"
  attributes:
    label: "检查项"
    description: "请逐个检查下列项目，并勾选确认。"
    options:
    - label: "我已在Issues 页面检查过，没有"
      required: true
- type: textarea
  id: "yml-2"
  attributes:
    label: 描述
    description: "详细描述该 Bug 的具体表现。"
  validations:
    required: true
- type: textarea
  id: "yml-3"
  attributes:
    label: 重现步骤
    description: "详细描述要怎么操作才能再次触发这个 Bug。"
    value: |
      1、点击xxxx
      2、往下滚，然后点击xxxx
  validations:
    required: true
- type: textarea

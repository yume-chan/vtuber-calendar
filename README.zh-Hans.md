[English](README.md)

# 在线查看

[点我](https://outlook.live.com/owa//calendar/00000000-0000-0000-0000-000000000000/ebe488fe-d22e-4d53-8db6-249d726f30b0/cid-3B22DB901DF4622D/index.html)

# 添加到日历程序

订阅[此 ICS 连接](https://outlook.live.com/owa//calendar/00000000-0000-0000-0000-000000000000/ebe488fe-d22e-4d53-8db6-249d726f30b0/cid-3B22DB901DF4622D/calendar.ics)

Outlook.com 用户: [在 Outlook.com 中导入或订阅日历](https://support.office.com/zh-cn/article/import-or-subscribe-to-a-calendar-in-outlook-com-cff1429c-5af6-41ec-a5b4-74f2c278e98c)

其它程序用户: 请查看日历提供商的帮助文档

# 贡献

有两种贡献方式

## 如果你有任何修改的提案

[提交 issue](https://github.com/yume-chan/vtuber-calendar/issues/new/choose).

## 如果你想帮忙维护此日历

本日历托管在 Outlook 上，所以你需要一个 Microsoft Account。

请带上你的 Microsoft Account 提交 issue，或以邮件方式联系我。我将为你添加编辑权限。

# 规则

## 标题: *name*\[ - *title*]
* *name*: 一个 vtuber 的名字.
  如果是联动活动，使用将会直播的 vtuber 的名字。
  如果有复数将会直播的 vtuber，创建多个日程。
* *title*: 官方发布的直播标题，不含任何标签。
  如果还没有官方发布的标题，可以使用官方的简介，或者直接忽略。

## 日期:
官方发布的开始日期，或者实际开始的日期。

如果官方还没有发布直播开始日期，则不能把该直播添加到本日历内。

## 时间: *start_time* - *end_time*
* *start_time*: 官方发布的开始时间，或者实际开始的时间。

  如果官方还没有发布开始时间，则把日程设为全天。
* *end_time*: 官方发布的结束时间，或者实际结束的时间。

  如果官方还没有发布结束时间，但是 *start_time* 不为空，则将 *end_time* 设为 *start_time* 后的一小时。

## 注释:

注释是一个 [YAML](https://docs.ansible.com/ansible/latest/reference_appendices/YAMLSyntax.html) 字典，包含额外信息.

目前可以包含以下字段:

### participants:

如果是联动活动，列出所有参与者的名字。

### references:

列出引用, 比如 Twitter 链接, YouTube 链接等.

# 其它有用的链接

* [VTuberスケジュールRTぼっと](https://twitter.com/vtuber_schedule) (VTuber 日程转推机器人，日语)

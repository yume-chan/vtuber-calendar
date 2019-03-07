[中文](README.zh-Hans.md)

# View online

[click me](https://outlook.live.com/owa//calendar/00000000-0000-0000-0000-000000000000/ebe488fe-d22e-4d53-8db6-249d726f30b0/cid-3B22DB901DF4622D/index.html)

# Add to your calendar app

Subscribe to [this ICS link](https://outlook.live.com/owa//calendar/00000000-0000-0000-0000-000000000000/ebe488fe-d22e-4d53-8db6-249d726f30b0/cid-3B22DB901DF4622D/calendar.ics)

For Outlook.com users: [Import or subscribe to a calendar in Outlook.com](https://support.office.com/en-us/article/import-or-subscribe-to-a-calendar-in-outlook-com-cff1429c-5af6-41ec-a5b4-74f2c278e98c)

For other users: please check your calendar providers' documentation.

# Contribute

There are two ways you can contribute.

## If you have any suggestions

Please [file an issue](https://github.com/yume-chan/vtuber-calendar/issues/new/choose).

## If you want to help me maintaining this calendar

This is an Outlook calendar, so you need a Microsoft Account.

Please file an issue with your Microsoft Account, or contact me by email. I will add edit permission to you.

# Convention

## Event title: *name*\[ - *title*]
* *name*: Exact one vtuber's name.
  If it's a collaboration event, use the name of vtuber that will boardcast the live stream.
  If multiple vtubers will boardcast this event, create multiple events.
* *title*: The official title of the event, without any tags.
  If no official title has been announced, can also be a short description or be omitted completely.

## Event date:
The officially announced start date, or the actual start date of the event, if it has already started.

If no official event date has been announced, this event can't be put into this calendar.

## Event time: *start_time* - *end_time*
* *start_time*: The officially announced start time, or the actual start time of the event, if it has already started.

  If no official start time has been announced, set the event to an all day event.
* *end_time*: The officially announced end time, or the actual end time of the event, if it has already ended.

  If no official end time has been announced, but the *start_time* is not empty, set the *end_time* to be one hour after *start_time*.

## Event description:

The description is a [YAML](https://docs.ansible.com/ansible/latest/reference_appendices/YAMLSyntax.html) dictionary that represents extra information.

It can contains these fields:

### participants:

If it's a collaboration event, list all participants' names here.

### references:

List of all official announcements, e.g. Twitter links, YouTube links, etc.

# Other useful links

* [VTuberスケジュールRTぼっと](https://twitter.com/vtuber_schedule) (VTuber schedule retweet bot, in Japanese)

---
title: Extra things of Calendar
lang: en
date: 2022-12-09
version: 0.1
nav-order: 55
category: Calendar
tags:
  - Cloud
  - Calendar
  - Attendees
  - Reminders
  - Event that repeats
  - Recurring event
  - Event Invitations
  - Appointments
---

## Invitations
### Sending invitations to an event

You may add attendees to an event to let them know they're invited. They will receive an email invitation and will be able to confirm or cancel their participation to the event. Attendees may be other users on your Nextcloud instances, contacts in your address books and direct email addresses. You may also change the level of participation per attendees, or disable the email information for a specific attendee.

![](https://docs.nextcloud.com/server/latest/user_manual/_images/calendar_event_invitation_level.png)

> When adding other Nextcloud users as attendees to an event, you may access their free-busy information if available, helping you determine when the best time slot for your event is. Set your `working hours<calendar-working-hours>` to let others know when you are available. Free-busy information is only available for other users on the same Nextcloud instance.

> Only the calendar owner can send out invitations. The sharees are not able to do that, whether they have write access to the event's calendar or not.

### Responding to invitations

You can directly respond to invitations inside the app. Click on the event and select your participation status. You can respond to an invitation by accepting, declining or accepting tentatively.

![](https://docs.nextcloud.com/server/latest/user_manual/_images/calendar_accept_simple_editor.png)

You can respond to an invitation from the sidebar too.

![](https://docs.nextcloud.com/server/latest/user_manual/_images/calendar_accept_sidebar_editor.png)

### Trash bin

If you delete events, tasks or a calendar in Calendar, your data is not gone yet. Instead, those items will be collected in a *trash bin*. This offers you to undo a deletion. After a period which defaults to 30 days (your administration may have changed this setting), those items will be deleted permanently. You can also permanently delete items earlier if you wish.

![](https://docs.nextcloud.com/server/latest/user_manual/_images/calendar_trash_bin.png)

The ``Empty trash bin`` buttons will wipe all trash bin contents in one step.

>The trash bin is only accessible from the Calendar app. Any connected application or app won't be able to display its contents. However, events, tasks and calendars deleted in connected applications or app will also end up in the trash bin.

---
title: Calendar
lang: en
date: 2022-12-09
version: 0.1
nav-order: 50
category: Calendar
tags:
  - Cloud
  - Calendar
---
# Calendars

Calendars of the HfG cloud allow creating, configure and share a calendar with other people (and allow them to see or to edit them). But they actually allow doing countless other things, some of them you probably don't know.

The [documentation on Nextcloud](https://docs.nextcloud.com/server/latest/user_manual/en/groupware/calendar.html#create-a-new-calendar) is a good source and make our job really easier. So, we are copying and editing it (stand: December 2022): that's the good part of Creative Commons Public License. Let's first have an overview on the basics:

* **[Managing calendars](#managing-your-calendars)**: where we explain how to create, share, publish, subscribe, import and export or delete a calendar.
* **[Managing Events or Meetings](#managing-events-or-meetings)**: where we explain the difference between an event (only one participant) and a meeting (more participants) and how to create, manage, set up reminders and make them recurring.
* **[Working with an E-Mail Client](./hfg-cloud-calendar-synch)**: Here we guide you to configure your Thunderbird, Apple Mail or smartphone so that you don't miss any appointment.

Here are some cool features, of which you had probably though “The HfG should have an app for that”:

3. Invitations
4. Availability
5. Appointments

When you first access the Calendar app, a default first calendar will be created for you with the name: 'personal':

![Screenshot of the calendar web app. On the top, there is a horizontal blue bar with some icons. On the left, a sidebar with different calendars. There is a table with days as columns and hours as rows. In different colors, some events.](https://docs.nextcloud.com/server/latest/user_manual/_images/calendar_application.png)

## Managing your calendars

### Create a new Calendar

If you intend to set up a new calendar without transferring any old data from your previous calendar, creating a new calendar is the way you should go.

![Screenshot of the calendar web app. This time with a focus on the sidebar, where there is a New calendar item and next to it, an icon with three points. Clicked, it offers a prompt with new calendar, new calendar with task list or new subscription from link (read only)](https://docs.nextcloud.com/server/latest/user_manual/_images/calendar_create_1.png)

1. Click on ``+ New Calendar`` in the left sidebar.

2. Type in a name for your new calendar, e.g., “Work”, “Home” or “Project's name”.

3. After clicking on the checkmark, your new calendar is created and can be synced across your devices, filled with new events and shared with your friends and circles.

![The same prompted menu as in the image before. This time, the option new calendar is a text field (for the name of the calendar) with an arrow next to it.](https://docs.nextcloud.com/server/latest/user_manual/_images/calendar_create_2.png)

### Import a Calendar

If you want to transfer your calendar and their respective events to your Nextcloud instance, importing is the best way to do so.

![Screenshot, now focusing in the bottom part of the sidebar (Calendar setting): A big button, with Import calendar and them some checkboxes: Enable birthday calendar, enable simplified editor, limit visible events per view, Show weekends, Show week numbers.](https://docs.nextcloud.com/server/latest/user_manual/_images/calendar_settings.png)

1. Click on the settings-icon labeled with ``Settings & Import`` at the left-bottom.

2. After clicking on ``+ Import Calendar`` you can select one or more calendar files from your local device to upload.

3. The upload can take some time and depends on how big the calendar you import is.

### Edit, Export or Delete a Calendar

Occasionally, you may want to change the color or the entire name of a previous imported or created calendar. You may also want to export it to your local hard drive or delete it forever.

> Deleting a calendar is a irreversible action. After deletion, there is no way of restoring the calendar unless you have a local backup.

![Top of the sidebar of calendars: After a button with two arrows with the week (Week 44 of 2022), buttons to create New event, jump to today or edit the view mode of the calendar. After it, the different calendars, preceded by a dot with a color (appointment with violet, Personal with blue, Public events with orange, Work with light brown, Project (Bob) with turquoise). Another calendar, Fenchurch Lunch, is deactivated, and the dot is just a pink circle, not filled. On the right of each calendar there is an icon: either of three points, or share (represented by three connected dots forming a triangle) or a link (represented by a chain). Near Project Bob, the icon is a B, with a small moon as a status-icon on the bottom right.](https://docs.nextcloud.com/server/latest/user_manual/_images/calendar_dropdown.png)

Click on the three-dot-menu of the respective calendar.

![Similar menu as the previous screenshot, this time the icon with the three buttons next to Appointments is clicked, and a prompt menu is open: Edit name, Edit column (both with a pencil icon), copy private link (with  a chain as icon), export (with an arrow pointing down icon) and a trash bin silhouette to delete.](https://docs.nextcloud.com/server/latest/user_manual/_images/calendar_editing.png)

Click on *Edit name*, *Edit color*, *Export* or *Delete*.

### Sharing calendars

You may share your calendar with other users or groups. Calendars may be shared with write access or read-only. When sharing a calendar with write access, users with whom the calendar is shared will be able to create new events into the calendar as well as edit and delete existing ones.

> Calendar shares currently cannot be accepted or rejected. If you want to stop having a calendar that someone shared with you, you can click on the 3-dot menu next to the calendar in the calendar list and click on "Unshare from me". Calendars shared with a group cannot be unshared by individuals.

### Publishing a calendar

Calendars can be published through a public link to make them viewable (read-only) to external users. You may create a public link by opening the share menu for a calendar and clicking on '+' next to 'Share link'. Once created, you can copy the public link to your clipboard or send it through email.

There's also an 'embedding code' that provides an HTML iframe to embed your calendar into public pages.


### Subscribe to a Calendar

You can subscribe to iCal calendars directly inside your Nextcloud. By supporting this interoperable standard (RFC 5545) we made Nextcloud calendar compatible to Google Calendar, Apple iCloud and many other calendar-servers you can exchange your calendars with, including subscription links from calendar published on other Nextcloud instances, as described above.

1. Click on ``+ New Subscription`` in the left sidebar.
2. Type in or paste the link of the shared calendar you want to subscribe to.

Finished. Your calendar subscriptions will be updated regularly.

> Subscriptions are refreshed every week by default. Your administrator may have changed this setting.

***

# Managing Events or Meetings

## Create a new event

Events can be created by clicking in the area when the event is scheduled. In the day- and week-view of the calendar, you just click, pull and release your cursor over the area when the event is taking place.

![Screenshot of the Event-Menu superposed to the calendar view. On the header of the window, are represented two paper-holders. It follows a text field with the title of the event (Find Major Lewi's Lucky Shorts!) and a field to select the calendar (Public Events, preceded with an orange circle). Thereafter, two date hour fields (from and to, both with a world icon), settled at 05.11.2022 10:00 to same day 10:30. Then a checkbox for selecting all day. Another text field to add a location, with a location icon, consisting of a circle enlarged to the bottom part. Subsequently, a Description text field, preceded with a square with some lines. After, two buttons fore more and save in dark blue](https://docs.nextcloud.com/server/latest/user_manual/_images/calendar_new-event_week.png)

The month-view only requires a single click into the area of the target day.

![Another screenshot of an event-prompt. This time in the header are represented two people, blond in front of each other. Above them, some rectangles, probably representing documents. The Event is called Meeting about tent improvement for Linus and is settled for 08.11.2022 10:00-11:00](https://docs.nextcloud.com/server/latest/user_manual/_images/calendar_new-event_month.png)

Now, you can type in the event's name, choose the calendar in which you want to save the event to (e.g., **Personal**, **work**), define the time span or set the event as an all-day event. Optionally, you can specify a location and a description.

If you wish to edit advanced details such as the **Attendees** or **Reminders**, or if you wish to set the event as a repeating-event, click on the ``More`` button to open the advanced
sidebar editor.

> If you always want to open the advanced sidebar editor instead of the simple event editor popup, you can set a ``Skip simple event editor`` checkmark in the ``Settings & Import`` section of the app.

Clicking on the blue ``Create`` button will finally create the event.

### Edit, duplicate or delete an event

If you intend to edit, duplicate or delete a specific event, you first need to click on the event.

Thereafter, you will be able to re-set all event details and open the
advanced sidebar-editor by clicking on ``More``.

Clicking on the ``Update`` button will update the event. To cancel your changes, click on the close icon on the top right of the popup or sidebar editor.

If you open the sidebar view and click the three dot menu next to the event name, you have an option to export the event as an ``.ics`` file or remove the event from your calendar.

![Again, a prompt of the event, open in a right-sidebar. This time we see the same people as in the previous one, now sitting in front of each other. Next to the title (Meeting with Alice and Bob, the icon with three dashes is clicked, offering the options Export, Duplicate and Delete). In the bottom part, there are three more icons: Details (with an i inside a circle, Attendees with an icon of two users and Resources, with the location icon).](https://docs.nextcloud.com/server/latest/user_manual/_images/calendar_event_menu.png)

> If you delete events, they will go into your `trash bin`. You can restore accidentally deleted events there.

You can also export, duplicate or delete an event from the basic editor.

![Almost the same image as before, this time as a prompt in calendar: this time the background of the header image is gray (and not white). Near the three dots, there is an x to close the prompt. The icons at the bottom are no more visible.](https://docs.nextcloud.com/server/latest/user_manual/_images/calendar_event_menu_modal.png)

## Assign rooms and resources to an event
[This function is not activated in HfG Cloud]

## Set up reminders for events
You can set up reminders to be notified before an event occurs. Currently, supported notification methods are:

* Email notifications
* Nextcloud notifications

You may set reminders at a time relative to the event or at a specific date.

![A Screenshot of the details' menu: Location, Description with the icons described before. A thick with confirmed next to it, An icon of an eye with “When shared show full event”, A suitcase next to “Busy”, A tag near select or add categories; a color picker icon, near a brown square. A bell near the text 30 minutes before the event starts, with the icon of three dots next to it. Below, an input field to add a reminder. Then two arrows forming a circle next to no recurrence and thereafter, the icon of a pencil to edit it. At the bottom, an update blue button.](https://docs.nextcloud.com/server/latest/user_manual/_images/calendar_event_reminders.png)

> Only the calendar owner and people or groups with whom the calendar is shared with write access will get notifications. If you don't get any notifications but think you should, your Administrator could also have disabled this for your server.

> If you synchronize your calendar with mobile devices or other 3rd-party clients, notifications may also show up there.

## Add recurring options

An event may be set as “recurring” so that it can happen every day, week, month, or year. Specific rules can be added to set which day of the week the event happens or more complex rules, such as every fourth Wednesday of each month.

You can also tell when the recurrence ends.

![Another screenshot for the recurring events. On the top, near two arrows establishing a circle, Monthly on day 3 and a ticked icon. Then the text Repeat every with the text field 1 and selection field month. The radio button option is clicked, and after it, a month calendar is displayed with the day 3 in blue. The other radio option would be on the (text field) first (text field) Monday. After that End repeat and (as text field) never.](https://docs.nextcloud.com/server/latest/user_manual/_images/calendar_event_repeat.png)

If you edit one of the recurrences of the event, Nextcloud will ask you if you want to edit just this particular one, the future ones (from the one you selected) or all the occurrences (which includes past recurrences).

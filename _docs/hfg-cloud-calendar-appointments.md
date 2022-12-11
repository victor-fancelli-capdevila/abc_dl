---
title: Appointments
lang: en
date: 2022-12-09
version: 0.1
nav-order: 55
category: Calendar
tags:
  - Cloud
  - Calendar
  - Appointments
  - Sprechstunde, Organization of
---

# Appointments

> Did you tryied to set or get an appointment in the HfG? Or wanted to comunicate that you have _Sprechstunden_? Frustrating, isn't it? It's quite messy with a bak and forth of emails... Luckily, you can manage that with Nextcloud, improving the process. We got all the information from [Nextcloud Official Documentation](https://docs.nextcloud.com/server/latest/user_manual/en/groupware/calendar.html#appointments)

In this section we'll use the term *organizer* for the person who owns the calendar and sets up appointment slots. The *attendee* is the person who books one of the slots.

### Creating an appointment configuration

As an organizer of appointments [go to the HfG Calendar](https://cloud.hfg-karlsruhe.de/apps/calendar/). In the left sidebar you'll find a section for appointments, were you can open the dialogue to create a new one.

![](https://docs.nextcloud.com/server/latest/user_manual/_images/appointment_new.png)

One of the basic infos of every appointment is a title describing what the appointment is about (e.g. "Sprechstunde" if you are offering them), where an appointment will take place (can also be a link to BigBlueButton) and a more detailed description of what this appointment is about.

![](https://docs.nextcloud.com/server/latest/user_manual/_images/appointment_config_basics.png)

The duration of the appointment can be picked from a predefined list. Next, you can set the desired increment. The increment is the rate at which possible slots are available.
For example, you could have one hour long slots, but you give them away at 30 minute increments so an attendee can book at 9:00AM but also at 9:30AM.

Every booked appointment will be written into one of your calendars, so you can chose which one that should be. Appointments can be *public* or *private*:
* Public appointments can be discovered through the profile page of a Nextcloud user.
* Private appointments are only accessible to the people who receive the secret URL.

![](https://docs.nextcloud.com/server/latest/user_manual/_images/appointment_config_calendar_settings.png)

> Only slots that do not conflict with existing events in your conflict calendars will be shown to attendees: If you normally have appointments activated on Mondays morning, but you have another meeting (in the calendar), people will not be able to select that slot.

The organizer of an appointment can specify at which times of the week it's generally possible to book a slot. This could be the [working hours]() but also any other customized schedule.

Some appointments require time to prepare: The organizer can chose to select a time duration that must be free for preparation). Only slots that do not conflict with other events during the preparation time will be available. Moreover there is the option to specify a time after each appointment that has to be free.

To prevent an attendee from booking too short notice it's possible to configure how soon the next possible appointment might take place.
Setting a maximum number of slots per day can limit how many appointments are possibly booked by attendees.

![](https://docs.nextcloud.com/server/latest/user_manual/_images/appointment_config_limits.png)

The configured appointment will then be listed in the left sidebar. Via the three dot menu, you can preview the appointment. You can copy the link to the appointment and share it with your target attendees,
or let them discover your public appointment via the profile page. You can also edit or delete the appointment configuration.

![](https://docs.nextcloud.com/server/latest/user_manual/_images/appointment_config_options.png)

### Booking an appointment

The booking page shows an attendee the title, location, description and length of an appointment.

For a selected day there will be a list with all the possible time slots. On days with no available slots, too many conflicts or a reached daily maximum limit of already booked appointments, the list might be empty.

![](https://docs.nextcloud.com/server/latest/user_manual/_images/appointment_booking_1.png)

For the booking, attendees have to enter a name and an email address. Optionally they can also add a comment.

![](https://docs.nextcloud.com/server/latest/user_manual/_images/appointment_booking_2.png)

When the booking was successful, a confirmation dialogue will be shown to the attendee.

![](https://docs.nextcloud.com/server/latest/user_manual/_images/appointment_booking_3.png)

To verify that the attendee email address is valid, a confirmation email will be sent to them.

![](https://docs.nextcloud.com/server/latest/user_manual/_images/appointment_booking_confirmation_email.png)

Only after the attendee clicks the confirmation link from the email the appointment booking will be accepted and forwarded to the organizer.

![](https://docs.nextcloud.com/server/latest/user_manual/_images/appointment_booking_confirmation_dialogue.png)

The attendee will receive another email confirming the details of their appointment.

![](https://docs.nextcloud.com/server/latest/user_manual/_images/appointment_booking_email_2.png)

> If a slot has not been confirmed, it will still show up as bookable. Until then the time slot might also be booked by another user who confirms their booking earlier. The system will detect the conflict and offer to pick a new time slot.

### Working with the booked appointment

Once the booking is done, the organizer will find an event in their calendar with the appointment details and the attendee.

![](https://docs.nextcloud.com/server/latest/user_manual/_images/appointment_calendar_event.png)

If the appointment has the setting "Add time before event" or "Add time after the event" enabled, they will show up as separate events in the calendar for the organizer.

![](https://docs.nextcloud.com/server/latest/user_manual/_images/appointment_calendar_prep.png)

As with any other event that has attendees, changes and cancellations will trigger a notification to the attendee's email.

If attendees wish to cancel the appointment they have to get in contact with the organizer, so that the organizer can cancel or even delete the event.

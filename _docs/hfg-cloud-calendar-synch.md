---
title: Synching the calendar
lang: en
date: 2022-12-09
version: 0.1
nav-order: 60
category: Calendar
tags:
  - Cloud
  - Calendar
---
# Synchonizing Calendars

Here you will find the instructions to synchronize your calendars with:
* [Windows 10](#windows-10)
* [macOS](#macos)
* [GNU / Linux](#gnu--linux)
* [Thunderbird](#thunderbird)
* [iOS](#ios)
* [Android](#android)

As you're connecting a device with nextcloud, it's a good idea to [create an app password](hfg-cloud-log-in#app-password).

## Windows 10

1. In your browser, navigate to the Nextcloud Calendar app. Under “Settings & import”, copy the address using “Copy iOS/macOS CalDAV address” into your clipboard.
2. Launch the Windows 10 Calendar app. Then, click the settings icon (gear icon) and select “Manage accounts”.
3. Click “Add account” and choose “iCloud”.
4. Enter an email, username and password. None of this information has to be valid-it will all be changed in the upcoming steps.
5. Click “Done”. A message should appear indicating the settings were saved successfully.
6. In the “Manage Accounts” menu, click on the iCloud account created in previous steps, and select “Change settings”. Then, click on “Change mailbox sync settings”.
7. Scroll to the bottom of the dialog box, select “Advanced mailbox settings”. Scroll once more to the bottom of the dialog box and paste your CalDAV URL in the field labelled “Calendar server (CalDAV)”.
8. Click “Done”. Enter your Nextcloud username and password in the appropriate fields, and change the account name to whatever you prefer (e. g. “Nextcloud Calendar”). Click “Save”.

## macOS

In the following steps you will add your server resources for **CalDAV** (Calendar)
and **CardDAV** (Contacts) to your Nextcloud.

1. Open the **system preferences** of your macOS device.

2. Navigate to **Internet Accounts**:

![](https://docs.nextcloud.com/server/25/user_manual/_images/macos_1.png)


Click on **Add Other Account…** and click on **CalDAV Account** for Calendar
   or **CardDAV Account** for Contacts:

![](https://docs.nextcloud.com/server/25/user_manual/_images/macos_2.png)

> You can not setup Calendar/Contacts together. You need to setup them in **separate accounts**.

Select **Manual** as Account-Type and type in your respective credentials:
* **Username**: Your username with @hfg-karlsruhe.de
* **Password**: [Your generated app-password/token](hfg-cloud-log-in#app-password).
* **Server Address**: ``https://cloud.hfg-karlsruhe.de``

![](https://docs.nextcloud.com/server/25/user_manual/_images/macos_3.png)

Click on **Sign In**.

For **CalDAV (Calendar)**: You can now select, with which applications you want
to use this resource. In the most cases, this will be the "Calendar" application,
sometimes you may also want to use it for your **Tasks and reminders**.

![](https://docs.nextcloud.com/server/25/user_manual/_images/macos_4.png)

## GNU / Linux
It's well documented in the Official Documentation of Nextcloud, both for [GNOME](https://docs.nextcloud.com/server/25/user_manual/en/groupware/sync_gnome.html) and [KDE](https://docs.nextcloud.com/server/25/user_manual/en/groupware/sync_kde.html)


## Thunderbird

1. Go to the calendar
2. On the left pannel, click on the `+`near calendar`
3. Select `Network calendar`
4. Fill your username (with @hfg-karlsruhe.de) and as server write: `cloud.hfg-karlsruhe`. Check the offline option and let the no credentials option unchecked.
5. After a while it will ask for your password. Type it. Check to remember the password: if not, you will need to write everytime.
6. A window will appear, asking which calendars you want to synch (from all calendars that you can acess). Select the ones you want.
7. In the properties


## iOS

1. Open the settings application.
2. Select Calendar.
3. Select Accounts.
4. Select Add Account.
5. Select Other as account type.
6. Select Add CalDAV account.
7. For server, type `https://cloud.hfg-karlsruhe.de`.
8. Enter your user name (with @hfg-karlsruhe.de) and password.
9. Select Next.

Your calendar will now be visible in the Calendar application

## Android

### With the Nextcloud mobile app

1. Install [DAVx⁵ (formerly known as DAVDroid)](https://www.davx5.com/download/) on your Android device, [from Google Play Store](https://play.google.com/store/apps/details?id=at.bitfire.davdroid) or [from F-Droid](https://f-droid.org/packages/at.bitfire.davdroid/).
2. In the Nextcloud mobile, go to **Settings**/**More**, tap on "**Sync calendars & contacts**".
3. Now, DAVx⁵ will open Nextcloud's Webflow login window, where you will have to enter your credentials and grant access. Remember, [you can generate an App Pasword](./hfg-cloud-log-in#app-password)
4. DAVx⁵ will open and ask you to create an account. Set the account name to one of your choosing, and set **Contact Group Method** to **Groups are per-contact categories**.
5. After this, DAVx⁵ will close and the Nextcloud app reappears. In order to finish setup, you have to manually launch DAVx⁵ again.
6. Tap on the icon for the account DAVx⁵ has just created, when requested grant DAVx⁵ access to your calendars and contacts. Optionally install OpenTasks from [Google Play Store](https://play.google.com/store/apps/details?id=org.dmfs.tasks) or from [F-Droid](https://f-droid.org/packages/org.dmfs.tasks/) and grant DAVx⁵ access to your tasks, too.
7. When you tap the icon for the account DAVx⁵ has set up, it will discover the available address books and calendars. Choose whichones you want to synchronize and finish.

### Without the Nextcloud mobile app

If you do not want to install the Nextcloud mobile app, the following steps are required:

1. Install [DAVx⁵ (formerly known as DAVDroid)](https://www.davx5.com/download/) on your Android device, [from Google Play Store](https://play.google.com/store/apps/details?id=at.bitfire.davdroid) or [from F-Droid](https://f-droid.org/packages/at.bitfire.davdroid/).
2. Optionally install OpenTasks from [Google Play Store](https://play.google.com/store/apps/details?id=org.dmfs.tasks) or [F-Droid](https://f-droid.org/packages/org.dmfs.tasks/).
3. Create a new account ("+" button).
4. Select **Connection with URL and username**.
   **Base URL:** URL of your Nextcloud instance (e.g. ``https://sub.example.com/remote.php/dav``) and
   **Contact Group Method:** as credentials.
5. Choose the option ``Groups are per-contact categories``.
6. Click **Connect**.
7. Select the data you want to sync.
8. When requested, grant access permissions to DAVx⁵ for your contacts, calendars and optionally tasks.

> Enter your email address as DAVx⁵ account name (mandatory if you want to be able to send calendar invitation). If your email address is registered in your Nextcloud preferences and you have set up your account using the Nextcloud mobile app, this all should be aready the case.

> DAVx⁵ lists the calendar subscriptions made through the Nextcloud Calendar app, but you need to install the [ICSx⁵ (formerly known as ICSDroid)](https://icsx5.bitfire.at/) app on your Android device, [from the Google Play Store](https://play.google.com/store/apps/details?id=at.bitfire.icsdroid) or [from F-Droid](https://f-droid.org/packages/at.bitfire.icsdroid/) to sync them.
Synchronizing with Thunderbird

---
title: E-Mail
lang: en
date: 2022-10-2
version: 0.1
nav-order: 30
tags:
  - E-Mail
  - Webmail
---
# Accessing and configuring the HfG Email

There are different ways of accessing your E-Mail at the HfG:

## Through Horde
Go to [webmail.hfg-karlsruhe.de](https://webmail.hfg-karlsruhe.de) an log in with your username (without @hfg-kalrsruhe.de) and password. For a long time (you can see that in the interface), this has been the main access to E-Mail for the HfG commnity, so lot of people may refer to this Webmail when they speak of "Mail of the HfG". One of the main advantages is that the configuration is made out of the box, and you only need some tuning.

## Through HfG-Cloud
Go to [cloud.hfg-karlsruhe.de](https://cloud.hfg-karlsruhe.de) an log in with username **with @hfg-karlsruhe.de** and password. This is the Mail integrated in the cloud, and that is it's main advantage (that you have it together with shared calendars and files). One of the main advantages is that the configuration is made out of the box, and you only need some tuning.

## Through an E-Mail Client

> An E-Mail client is a program installed in your computer that synchronizes a Mail folder in your computer with the one in the server. Normally is practical, because allow a better integration in your computer and allows you to work without be dependent on an internet connection.

You need an E-Mail Client installed on your Desktop. Lots of Operating System offer a mail client (AppleMail, Outlook, Evolution, etc.). If you search a easy, modular and free (as in gratis and as in Mozilla Public License) E-Mail client for all platforms, we recommend [Mozilla Thunderbird](https://www.thunderbird.net/en-US/download/); for Android devices, [K9 -Mail](https://k9mail.app/download). Check below the instructions for configuring it.

# Basic E-Mail Configuration
## Signature
A signature is a text that will be displayed always under your emails and will display information about you or the institution you're working. It's useful to help people understand who you are and in which role you're writing. Some institutions may have a guideline for it. As far as we know, the HfG hasn't but a good recommendation would be:

```
///////
Staatliche Hochschule für Gestaltung Karlsruhe
Karlsruhe University of Arts and Design

Name
Role
Department

Lorenzstraße 15, 76135 Karlsruhe
working telephone number
yourmail@hfg-karlsruhe.de
```

Yes, it seems wired but you write your Email in a E-Mail Signature. That is related to a time when people was printing E-Mails. Of course, you can modify it as you will. Some people may use a signature with HTML and, for example an image on it: this may cause incompatibilities, but your signature is completely up to you.





# Configuring the Email-Client
Once you installed the Mail client, you may need to configure it. Sometimes, writing your name and E-Mail everything works fine, but here the configuration data if you need it:

| |Incoming Server | Outgoing server | What's that? |
| :--- | :---: | :---: | ---: |
| Protocol | IMAP | SMTP | The protocol (the "language") used for the communication between server and the client. Even if not recommended, POP3 could also be an option for incoming server: than all the mails will be downloaded into your computer and deleted from the server, and you will not find them if you connect with another device |
| Hostname | imap.hfg-karlsruhe.de | smtp.hfg-karlsruhe.de | The address where the server is |
| Port | 143 | 587 | Which door should it use to access the server? A server have different doors, depending on what protocol is using, if it has to go in or out, security level etc. |
| Connection Security | STARTTLS | STARTTLS |
| Username | email WITHOUT (hfg-karlsruhe) | email WITHOUT (hfg-karlsruhe) | The server needs to know who you are to connect you with your Emails (and not with from someone else)|
| Authentication method | Normal password |	Normal password | How will the server know that it is really you who wants to access your E-Mails? (You will tell the password) |

## Extra Configuration

### Calendars & tasks
Location 	https://cloud.hfg-karlsruhe.de/remote.php/dav/calendars/username@hfg-karlsruhe.de

Put your password in prompt

### Address book


## Filters

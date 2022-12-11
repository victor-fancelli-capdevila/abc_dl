---
title: Configuring the Email
title_short: Configuration
lang: en
date: 2022-10-2
version: 0.1
category: Mail
nav-order: 20
tags:
  - Email
  - Email-Client
  -
---

# Configuring an Email-Client
Once you installed the Mail client, you may need to configure it. Sometimes, writing your name and E-Mail everything works fine, but here the configuration data if you need it:

| |Incoming Server | Outgoing server | What's that? |
| :--- | :---: | :---: | ---: |
| Protocol | IMAP | SMTP | The protocol (the "language") used for the communication between server and the client. Even if not recommended, POP3 could also be an option for incoming server: than all the mails will be downloaded into your computer and deleted from the server, and you will not find them if you connect with another device |
| Hostname | imap.hfg-karlsruhe.de | smtp.hfg-karlsruhe.de | The address where the server is |
| Port | 143 | 587 | Which door should it use to access the server? A server have different doors, depending on what protocol is using, if it has to go in or out, security level etc. |
| Connection Security | STARTTLS | STARTTLS |
| Username | email WITHOUT (hfg-karlsruhe) | email WITHOUT (hfg-karlsruhe) | The server needs to know who you are to connect you with your Emails (and not with from someone else)|
| Authentication method | Normal password |	Normal password | How will the server know that it is really you who wants to access your E-Mails? (You will tell the password) |


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


## Extra Configuration

### Calendars & tasks
Location 	https://cloud.hfg-karlsruhe.de/remote.php/dav/calendars/username@hfg-karlsruhe.de

Put your password in prompt

### Address book


## Filters

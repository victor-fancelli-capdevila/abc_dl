---
title: Eduroam
lang: en
date: 2022-10-15
version: 0.1
nav-order:
tags:
  - Wi-Fi
  - Internet
---

# Eduroam

{% include translator.html %}


## What is eduroam (and why I need it)?

## Installation and configuration
Available information here: [http://accounts.hfg-karlsruhe.de](http://accounts.hfg-karlsruhe.de "Accountswebsite of the HfG") after login in.

### Windows Installation (works with Windows 10, probably 11)
 > Windows installation is a bit tricky, but we have this step-by-step guide.

On the Windows Menu (or Windows-key), search for Panel Control (Systemsteuerung), and there click on Network and Intenet (Netzwerke und Internet). Now you should see something like:

![](assets/img/docs/eduroam-windows-02.png)

Now click on "Create new connection or new network" (Neue Verbinung oder neues Netzwerk einrichten). This will appear:

![](assets/img/docs/eduroam-windows-03.png)

Yes, all the options seems quite similar, but you want the third one (establish Manual connection to a wireless network?), and hence we selected it. This will appear:

![](assets/img/docs/eduroam-windows-04.png)

The name should be "eduroam" or "eduroam-hfg" (no matter if you're using uppercase) and WPA2-Enterprise. Click on next.

![](assets/img/docs/eduroam-windows-05.png)

Now the tricky part: You will come back to the Panel control and the first link will allow us to change the configuration (or something like that). Yes, it makes no sense, Windows: assuming we started a manual configuration and you didn't give any possibility to configure it.. yes, we want to change the configuration you automatically created. After clicking on the link, something like that should appear (don't worry if your data is different):

![](assets/img/docs/eduroam-windows-06.png)

Just ignore it here and go to the "Security" tab. We can check the first part from our checklist:
- [x] WPA2-Enterprise
- [X] AES
Now select `Microsoft: EAP-TTLS` from the dropdown menu and then click on `Configuration`, which looks like:

![](assets/img/docs/eduroam-windows-07.png)

Please check that everything is correct

- [ ] Anonymity protection checkbox is activated
- [ ] Anonymity Identity is `anonymous@hfg-karlsruhe.de`
- [ ] Connection to server is set to `radius.hfg-karlsruhe.de`
- [ ] You checked the T-TeleSec Global Root Certificate (you should check in the list)
- [ ] Check also the thing after that
- [ ] Check the EAP-(External?) Authentification method and set to PAP (sometimes this and the next appear to change positions...)

Click on Ok, after the configuration. Small yeah! we still need a couple of things. So we're back in the Security tab:

![](assets/img/docs/eduroam-windows-06.png)

and we want to click in Advanced Options:

![](assets/img/docs/eduroam-windows-08.png)

Here you want to have the first checkbox activated, and select User-Authentication. Then click on the button after it, "Save Log-in information", this will happen:

![](assets/img/docs/eduroam-windows-09.png)

- **Login**: your username (everything before @hfg-karlsruhe.de)
- **Password** the E-Mail password.

Click ok.
Now you can go to the wireless symbol in the bar and try to connect normally. It may ask you again log-in and password, and then it should work.

So, congratulations, no you have internet (almost) everywhere!

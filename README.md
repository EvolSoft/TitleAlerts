![start2](https://cloud.githubusercontent.com/assets/10303538/6315586/9463fa5c-ba06-11e4-8f30-ce7d8219c27d.png)

# TitleAlerts

A PocketMine-MP plugin that shows alerts in titles using CustomAlerts API

## Category

PocketMine-MP plugins

## Requirements

PocketMine-MP 1.7dev API 3.0.0-ALPHA7, 3.0.0-ALPHA8, 3.0.0-ALPHA9, 3.0.0-ALPHA10<br>
**Dependency Plugins:** CustomAlerts v1.8 API 2.0

## Overview

**TitleAlerts** is a CustomAlerts extension which let you show alerts (like join/leave messages, etc...) in titles!

**EvolSoft Website:** https://www.evolsoft.tk

***This Plugin is a CustomAlerts extension and uses CustomAlerts API 2.0. THIS MEANS THAT YOU NEED TO INSTALL CustomAlerts v1.8 PLUGIN TO USE TitleAlerts***

Messages can be configured simply from the CustomAlerts configuration file<br>
Please read the documentation to see how to configure TitleAlerts

## Donate

Support the development of this plugin with a small donation by clicking [:dollar: here](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=flavius.c.1999@gmail.com&lc=US&item_name=www.evolsoft.tk&no_note=0&cn=&curency_code=EUR&bn=PP-DonationsBF:btn_donateCC_LG.gif:NonHosted). Thank you :smile:

## Documentation 

**Configuration (config.yml):**

```yaml
---
#Message text must be configured from default CustomAlerts config.yml file
#Join messages
Join:
  #Show join messages in titles
  show-title: true
  #Hide default join messages (they won't be displayed in chat but only on titles)
  hide-default: true
#Quit messages
Quit:
  #Show quit messages in titles
  show-title: true
  #Hide default quit messages (they won't be displayed in chat but only on titles)
  hide-default: true
#World Change messages (they are displayed only if they are enabled in CustomAlerts configuration)
WorldChange:
  #Show world change messages in titles
  show-title: true
  #Hide default world change messages (they won't be displayed in chat but only on titles)
  hide-default: true
#Death messages
Death:
  #Show death messages in titles (Remember that they can't be displayed from the victim)
  show-title: true
  #Hide default death messages (they won't be displayed in chat but only on titles)
  hide-default: true
...
```
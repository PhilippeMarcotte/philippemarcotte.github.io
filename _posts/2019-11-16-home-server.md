---
title: Home NAS
layout: post
date-made: Summer 2019
tag:
- network
headerImage: true
projects: true
hidden: false
description:
category: software
author: philippemarcotte
externalLink: https://minous.club
order: 2
---

In my free time, I made my own server running Ubuntu 18.04 headless on an Odroid HC2. I run multiple services like a password manager (Bitwarden), cloud storage (Nextcloud) and multimedia player (Plex). All these services are compartmentalized in docker containers. Outside network traffic is manage through a reverse-proxy (Nginx) and secure https connection is done with the help of Lets encrypt. Automated incremental backups to external hard drive are done using borg-backup and redundant backups of the password manager database are sent to Google Drive.

---
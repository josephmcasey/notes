---
attachments: [rc.local.png, system_rc-local.service.png, systemctl rc-local.png]
tags: [git, Notebooks/Local, ubuntu]
title: Setup Notable on Ubuntu with synchronization to remote git
created: '2021-08-28T17:24:08.035Z'
modified: '2021-08-30T22:38:23.443Z'
---

# Setup Notable on Ubuntu with synchronization to remote git




![/etc/rc.local](@attachment/rc.local.png)

![/etc/systemd/system/rc-local.service](@attachment/system_rc-local.service.png)

![systemctl list-units rc-local.service](@attachment/systemctl rc-local.png)

--- 

### Resources
- [gitwatch](https://github.com/gitwatch/gitwatch#what-to-use-it-for)
- [Example of Notes](https://github.com/josephmcasey/notes)
- [inotifywait Manual](https://linux.die.net/man/1/inotifywait)
- [Git Repo for inotify-tools](https://github.com/inotify-tools/inotify-tools)
- [Linux Wiki - Systemd Writing Unit Files](https://wiki.archlinux.org/title/Systemd#Writing_unit_files)
- [Notable - Note App](https://github.com/notable/notable)
- [Redhat Article](https://www.redhat.com/sysadmin/replacing-rclocal-systemd)


### Article Titles:
- Opinion: Notes on Local Environment for Software Development
- Setup Notable on Ubuntu to automtically commit notes to remote


### Ideas
- Perpetuate notes committed to GitHub and automatically reformat markdown files to GitHub Pages Website
- For companies, each organization in GitHub could have a single note repository that every person on a software team helps write and maintain, acting as an intermediary to a team wiki

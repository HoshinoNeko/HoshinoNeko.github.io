---
title: Make Normal user run wireshark correctly on Linux
date: 2021-06-14 16:54:35
tags:
---
```
sudo gpasswd -a `whoami` wireshark && sudo chgrp wireshark /usr/bin/dumpcap && sudo chmod 4755 /usr/bin/dumpcap
```

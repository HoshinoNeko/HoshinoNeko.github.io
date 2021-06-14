---
title: Make Normal user run wireshark correctly on Linux
date: 2021-06-14 16:54:35
tags:
---
```
sudo gpasswd -a `whoami` wireshark # Add current user to group wireshart
sudo chgrp wireshark /usr/bin/dumpcap # Update group of file /usr/bin/dumpcap to chgrp
sudo chmod 4755 /usr/bin/dumpcap # Update permission of /usr/bin/dumpcap to 4755
```

# CFEngine masterfiles

This repository contains the masterfiles for the CFEngine version in use in my set-up. The files are
extracted from the deb package. This is an example for v3.24.2

```commandline
wget https://cfengine-package-repos.s3.amazonaws.com/community_binaries/Community-3.24.2/agent_debian12_x86_64/cfengine-community_3.24.2-1.debian12_amd64.deb
dpkg -x cfengine-community_3.24.2-1.debian12_amd64.deb ./cfengine-3.24.2
rm -rf masterfiles/ && mv cfengine-3.24.2/var/cfengine/share/CoreBase/masterfiles .
```

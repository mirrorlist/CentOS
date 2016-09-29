#Centos repo

## Usage

Add `/etc/yum.repos.d/github.repo`

```ini
[github]
gpgcheck=0
name = Red Hat Linux $releasever - $basearch - GitHub
baseurl=https://mirrorlist.github.io/centos/6.8/
```

```
yum clean all
yum repolist all
```

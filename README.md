# Centos repo

## Usage

Add `/etc/yum.repos.d/mirror.repo`

```ini
[mirror]
gpgcheck=0
name = Red Hat Linux $releasever - $basearch - mirror
baseurl=https://mirrorlist.github.io/centos/6.8/
```

```
yum clean all
yum repolist all
```

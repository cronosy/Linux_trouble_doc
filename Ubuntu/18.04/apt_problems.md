# Apt 

## Description

APT is the tool to install packages from repositories in Ubuntu.

## Issues

### apt stuck in 0%[waiting headers]

After executing the next validations:
- Check that `ping` resolves domains.
- Validate `nslookup` resolves the URL.

I could conclude that DNS is working and connectivity too. So after reading comments in the next forum: `https://askubuntu.com/questions/156650/apt-get-update-very-slow-stuck-at-waiting-for-headers` Some comments mentioned the MTU inconsistency. 

#### Solution

use `ip link dev <interface> set mtu 1440` then all applications that use HTTP and HTTPS protocols start to work

```
curl -v http://
apt update
```
# nobk-overlay
gentoo ebuilds

- Install
```
sudo nano /etc/portage/repos.conf/nobk-overlay.conf
```

```
[nobk-overlay]
location = /usr/local/portage/nobk-overlay
sync-type=git
sync-uri=https://github.com/nobk/overlay.git
auto-sync = yes
priority = 50
```
```
sudo emaint sync --repo nobk-overlay
```
- Use
```
sudo emerge plzip
```

**WORK IN PROGRESS**

- kernel is able to be booted
- working display and touch
- can boot into xfce4
  - in `/etc/lightdm/lightdm.conf` set `logind-check-graphical=false`
  - in `/etc/pulse/default.pa` comment everything out (it crashes after logging in otherwise)

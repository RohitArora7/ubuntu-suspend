# ubuntu-suspend

```bash
sudo systemctl mask sleep.target suspend.target hibernate.target hybrid-sleep.target

sudo systemctl unmask sleep.target suspend.target hibernate.target hybrid-sleep.target
```


```bash
sudo vim /etc/systemd/logind.conf

HandleSuspendKey=ignore
HandleLidSwitch=ignore
HandleLidSwitchDocked=ignore


LidSwitchIgnoreInhibited=no


```

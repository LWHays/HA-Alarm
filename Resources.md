Alarm Examples
https://community.konnected.io/t/i-wrote-a-step-by-step-tutorial-on-how-to-bring-up-a-home-assistant-alarm-panel/24476
https://community.home-assistant.io/t/what-features-are-core-users-missing/202509
https://konnected.io/pages/home-assistant
Set up an alarm system with Home Assistant and Alarmo https://www.youtube.com/watch?v=oT-Pa-6gnfQ


HA operating system options:
https://www.bentasker.co.uk/posts/blog/general/migrating-from-homeassistant-os-to-homeassistant-in-docker.html
https://community.home-assistant.io/t/what-is-the-difference-between-a-dedicated-home-assistant-os-install-and-a-supervised-install/395684
Living without Add-Ons - Home Assistant Container  https://www.youtube.com/watch?v=DV_OD4OPKno
Which Home Assistant install is right for you?  https://www.youtube.com/watch?v=i72K1wyuTfg
Home Assistant installation methods compared: https://www.youtube.com/watch?v=HF6fd5Oi1N8
HA Core vs Supervisor (supervised???)   https://www.reddit.com/r/homeassistant/comments/honnfy/ha_core_vs_supervisor_whats_the_difference_beyond/
https://www.home-assistant.io/installation/

Syslog to external device:
https://www.home-assistant.io/integrations/syslog/
https://community.home-assistant.io/t/wth-is-there-no-home-assistant-logs-to-remote-syslog-integration/473949/5
https://community.home-assistant.io/t/wth-any-and-all-log-should-be-able-to-redirect-to-syslog-natively/477177
https://community.home-assistant.io/t/export-logs-to-a-remote-syslog/267360/2
https://community.home-assistant.io/t/external-syslog-server/48104/12
https://community.home-assistant.io/t/syslog-notifications-where-is-the-syslog/392845
https://community.home-assistant.io/t/home-assistant-add-on-promtail/293732
https://github.com/bertbaron/hassio-addons/tree/main/logspout

Hardware:
Deep Dive of Home Assistant installations and hardware options https://www.youtube.com/watch?v=Q2QW3JzLp58

Notes from Ed:
...
Assuming the Pi 3B has 1 GB of RAM

If you are planning on using a Raspberry Pi to run Home Assistant, it is recommended to use a Raspberry Pi 4 with at least 2GB of RAM. This will ensure that your Home Assistant instance has enough memory to run smoothly.Dec 11, 2022

Raspberry Pi 4 (Raspberry Pi 3 Model B is ok too, but the Model A does not have enough RAM).

Raspberry Pi 3 Model B is the earliest model of the third-generation Raspberry Pi. 
1GB RAM

Default - move to a different port to obfuscate, seems basic, as well as the default URL
port 8123
Just within your home network you might know that your Home Assistant is on an IP like 192.168. 1.4 and listening on port 8123. If you use Home Assistant OS and haven't changed any of the defaults, Home Assistant will also be reachable at http://homeassistant.local:8123.
...


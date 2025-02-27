Alarm Examples
- https://community.konnected.io/t/i-wrote-a-step-by-step-tutorial-on-how-to-bring-up-a-home-assistant-alarm-panel/24476
- https://community.home-assistant.io/t/what-features-are-core-users-missing/202509
- https://konnected.io/pages/home-assistant
- https://github.com/nielsfaber/alarmo-card/issues/89
- https://www.juanmtech.com/set-up-an-alarm-system-with-home-assistant-and-alarmo/#alarmo-custom-alarm-card
- 
Set up an alarm system with Home Assistant and Alarmo https://www.youtube.com/watch?v=oT-Pa-6gnfQ

Alarm sensors integration:
- https://support.konnected.io/alarm-panel-pro-conversion-kit
- https://konnected.io/products/konnected-alarm-panel-pro-12-zone-kit
- https://support.konnected.io/konnected-alarm-panel-pro-conversion-kit-installation-guide
- https://www.home-assistant.io/integrations/konnected/
- https://community.home-assistant.io/t/trouble-inverting-value-from-door-sensor/660070   Inverting values
  
HA operating system options:
- https://www.bentasker.co.uk/posts/blog/general/migrating-from-homeassistant-os-to-homeassistant-in-docker.html
- https://community.home-assistant.io/t/what-is-the-difference-between-a-dedicated-home-assistant-os-install-and-a-supervised-install/395684
- Living without Add-Ons - Home Assistant Container  https://www.youtube.com/watch?v=DV_OD4OPKno
- Which Home Assistant install is right for you?  https://www.youtube.com/watch?v=i72K1wyuTfg
- Home Assistant installation methods compared: https://www.youtube.com/watch?v=HF6fd5Oi1N8
HA Core vs Supervisor (supervised???)
- https://www.reddit.com/r/homeassistant/comments/honnfy/ha_core_vs_supervisor_whats_the_difference_beyond/
- https://www.home-assistant.io/installation/

Syslog to external device:
- https://www.home-assistant.io/integrations/syslog/
- https://community.home-assistant.io/t/wth-is-there-no-home-assistant-logs-to-remote-syslog-integration/473949/5
- https://community.home-assistant.io/t/wth-any-and-all-log-should-be-able-to-redirect-to-syslog-natively/477177
- https://community.home-assistant.io/t/export-logs-to-a-remote-syslog/267360/2
- https://community.home-assistant.io/t/external-syslog-server/48104/12
- https://community.home-assistant.io/t/syslog-notifications-where-is-the-syslog/392845
- https://community.home-assistant.io/t/home-assistant-add-on-promtail/293732
- https://github.com/bertbaron/hassio-addons/tree/main/logspout
- https://github.com/TheByteStuff/RemoteSyslog_Service/blob/main/GarageDoorOpenExample.png
- https://github.com/TheByteStuff/RemoteSyslog_Service?tab=readme-ov-file

Hardware:
Deep Dive of Home Assistant installations and hardware options 
- https://www.youtube.com/watch?v=Q2QW3JzLp58

UI:
Alarm panel, HA standard:
- https://www.home-assistant.io/dashboards/alarm-panel/
Dashboard modifications:
- https://youtu.be/gouMnPxYHDc?si=cWcs35kBhF8WiSJ0    totally custom dashboard, easy mode (mushroom)
- https://youtu.be/A0fMt8IRKoI?si=nh_9MXWguhvPcj7T    totally custom dashboard, hard mode (minimalist)
- https://community.home-assistant.io/t/mushroom-cards-build-a-beautiful-dashboard-easily-part-1/388590/43 Mushroom
Custom Card:
- https://developers.home-assistant.io/docs/frontend/custom-ui/custom-card/
- https://developers.home-assistant.io/docs/frontend/custom-ui/custom-card-feature/  
- https://github.com/nielsfaber/alarmo-card/issues/89
- https://community.home-assistant.io/t/how-to-change-alarm-card-buttons-so-they-are-viewed-easily/511952
- https://community.home-assistant.io/t/custom-cards-with-gui-editor-as-of-2023/542254/4
- https://github.com/custom-cards/boilerplate-card
Kiosk mode: (
- https://community.home-assistant.io/t/kiosk-mode/425678/9
- https://github.com/maykar/kiosk-mode
- 

Duplicate PINs problem / other alarmo pin options:
- https://community.home-assistant.io/t/touchpad-for-manual-alarm-control-panel-supports-multiple-user-codes/357688
- 
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

GUI stuff

https://community.home-assistant.io/t/tutorials-how-to-develop-a-custom-card-and-ship-hacs-repositories/526566/10
https://github.com/home-assistant-tutorials


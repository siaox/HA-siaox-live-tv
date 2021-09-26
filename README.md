# Home Assistant One Click Live TV


Actionable Notifications for Sporting Events / Live TV Shows using Google Calendar Integration + Logitech Harmony

![example](https://i.ibb.co/QrBLGVL/siaox-live-tv.jpg)


**Sofware / Hardware Requirements**

1. Logitech Harmony Hub or a Broadlink - Using a Harmony Hub
2. Android Box  -  Using a NVIDIA Shield + Xiaomi Mi Box
3. Live TV / App - Using [TiviMate App](https://play.google.com/store/apps/details?id=ar.tvplayer.tv&hl=en&gl=US)
4. [Button Mapper](https://play.google.com/store/apps/details?id=flar2.homebutton&hl=en&gl=US) or [ADB Integration](https://www.home-assistant.io/integrations/androidtv/) on Home Assistant
5. Google Calendar with shows / events to trigger automations
6. [Home Asssitant Companion App](https://play.google.com/store/apps/details?id=io.homeassistant.companion.android&hl=en&gl=US)


**Home Assistant Integrations**


1. [Logitech Harmony](https://www.home-assistant.io/integrations/harmony/)
2. [Google Calendar](https://www.home-assistant.io/integrations/calendar.google/)




**Notes:**


- Activity / Device ID's can be found in `/config/harmonyxxxxx.conf`
- I have two TV's (Bar and TV Room) which have android boxes connected running an IPTV App ([TiviMate App](https://play.google.com/store/apps/details?id=ar.tvplayer.tv&hl=en&gl=US))
- I've comment the first script that will run the actionable notification and left the second  uncommented to avoid repetition.
- Android ADB is also an option for opening apps but I felt that since we're already using Harmony we could keep it simple. Had some issues using ADB with the Xiaomi Mi Box but Harmony commands work well. [Helpful ADB Shield Intents](https://gist.github.com/mcfrojd/9e6875e1db5c089b1e3ddeb7dba0f304)
- More info on [Actionable Notifications](https://companion.home-assistant.io/docs/notifications/actionable-notifications/)


**TiviMate Tips:**


- Use favourites
- For multiple devices / tv's with TiviMate  - Suggest backup and share across devices to use the same channel numbers.
 

Hope you guys have fun with this.
Thanks HA Community.




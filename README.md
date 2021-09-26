# HA-siaox-live-tv


Actionable Notifications for Sporting Events / Live TV Shows using Google Calendar Integration + Logitech Harmony


Sofware / Hardware Requirements:

1. Logitech Harmony Hub or a Broadlink - Using a Harmony Hub
2. Android Box  -  Using a NVIDIA Shield + Xiaomi Mi Box
3. Live TV / App - Using TiviMate App - https://play.google.com/store/apps/details?id=ar.tvplayer.tv&hl=en&gl=US
4. Button Mapper or ADB Integration on Home Assistant
5. Google Calendar with shows / events to trigger automations


Home Assistant Integrations:

1. Logitech Harmony - https://www.home-assistant.io/integrations/harmony/
2. Google Calendar - https://www.home-assistant.io/integrations/calendar.google/


Notes:

Activity / Device ID's can be found in /config/harmonyxxxxx.conf

I have two TV's (Bar and TV Room) which have android boxes connected running an IPTV App (TiviMate). 

I've comment the first script that will run the actionable notification and left the second  uncommented to avoid repetition.

Android ADB is also an option for opening apps but I felt that since we're already using Harmony we could keep it simple.



Hope you guys have fun with this.
Thanks HA Community.


[Buy me a Beer](https://www.buymeacoffee.com/siaox/ha-actionable-notifications-sports-live-tv)

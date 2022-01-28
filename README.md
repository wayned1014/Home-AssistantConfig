# Home Assistant Configuation
![GitHub last commit](https://img.shields.io/github/last-commit/wayned1014/Home-AssistantConfig)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/wayned1014/Home-AssistantConfig)
![HA Version](https://img.shields.io/badge/Running%20Home%20Asssistant-2021.12.10%20-darkblue)

I started back at the end of December 2020 using a RaspberryPi 4 with hassOS on a SD-Card and a Aeotec Z-Stick Gen5 Z-wave Plus USB

Six months later decided to upgrade:

Hardware:
- Intel NUC 7th Gen i5
- 32GB memory
- 500GB M.2 drive
- Aeotec Z-Stick Gen5 Z-wave Plus USB

Software:
- VMware ESXi
- On ESXi I am running the following VMs:
  - HassOS
  - AdGuard
  - MariaDB(for HA recorder)
  - Frigate(no Google Coral, only 1 camera right now)
  - Unitrends Backup(for backups, duh, of course!)
  - OwnTone(Music Streaming)
  - UniFi Network Application


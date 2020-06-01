## This repository is used for PlexMediaServer, Transmission and Monitorrent stack setup

Tested on: 
- Ubuntu 20.04
- Docker version 19.03.9
- docker-compose version 1.25.5

`Installation`
- git clone https://github.com/RealArtemiy/plex-transmission-monitorrent.git
- cd plex-transmission-monitorrent
- Open docker-compose and update [timezone](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones) and [plex claim](https://www.plex.tv/claim/)
- docker-compose up -d

`Configuration`
- Open http://127.0.0.1:32400/web/ for plex setup
- Open http://127.0.0.1:9091/ for transmission (username and password: admin / admin)
- Open http://127.0.0.1:6687/ for monitorrent (default password is monitorrent)

[Youtube video](https://youtu.be/FgVrmeazIGg)


`Used repositories`
1. https://github.com/plexinc/pms-docker
2. https://github.com/dperson/transmission
3. https://github.com/werwolfby/monitorrent

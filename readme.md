#Homeserver template

This is a docker compose template I created for my server at home providing 
me with some services I need as well as appropriate monitoring tools. 

It includes the following:

* Plex Media Server
* Timemachine for OSX backups
* Teamspeak
* Resilio Sync (formerly BitTorrent Sync)
* Route53-based IP mapping as an alternative to DynDNS for dynamic IP addresses.

Additionally, it incorporates the following monitoring system:

* Prometheus including the node exporter for machine metrics as well as
cAdvisor for container-specific metrics.
* Grafana for displaying useful charts on those metrics (charts still have to be defined manually atm).

I'm running an extended configuration of this happily on my "homeserver" (T400 running Ubuntu).

It's an initial configuration and everybody is different, so ymmv. Feel free to adapt it to your needs!
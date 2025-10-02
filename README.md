# AR-spatial-IP-starter
Postgres (DB): stores persistent stuff (notes, audits) if/when the services write to it.  Redis (real-time bus): configured with --notify-keyspace-events Ex so it emits events when TTL keys expire.  docker-compose.yml: one command brings up the stack the same way every time.

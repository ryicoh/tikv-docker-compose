# TiKV Docker Compose

**This environment is only suitable for development!**

**Note:** I have not removed references to TiDB specific metrics from Grafana.

Get a TiKV development environment up and running with minimal fuss.  This is a direct fork of PingCAP's handy
TiDB docker-compose, but without all of the DB parts.  Specifically, I have removed:

* TiDB
* TiSpark Master
* TiSpark Slave 0

## Quick Start

```bash
$ git clone https://github.com/wwwesleyyy/tikv-docker-compose.git
$ cd tidb-docker-compose && docker-compose pull
$ docker-compose up -d
```

## Included Tools

* Grafana runs on [port 3000](http://localhost:3000). Login with admin/admin to customize it.
* TiDB Vision runs on [port 8010](http://localhost:8010).

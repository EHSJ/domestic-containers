# Codex

[Back to Index](README.md)

## Pieces

[Automatization]: #Families "Automate task, builds and deploys"
[Blog]: #Families "Blog"
[DataBase]: #Families "Backend Databases"
[DockerAdmin]: #Families "Admin your docker server"
[Domotics]: #Families "Home automation"
[ERP]: #Families "Enterprise Resource Management"
[Git]: #Families "Git Server"
[Library]: #Families "eBooks, Comics & Documents library"
[Metrics]: #Families "Monitor your stuff"
[Multimedia]: #Families "Multimedia library"
[Others]: #Families
[Photo]: #Families "Photo library"
[RSS]: #Families "Feeds"
[ServiceHub]: #Families "Front end"
[SyncBox]: #Families "Sync your data"
[Onion]: #Families "Onnion routing"
[Torrent]: #Families "Download your stuff"
[VPN]: #Families "Be allways in your lan"
[WebServer]: #Families
[Wiki]: #Families

 [ofc]: #Tags "Official docker image available"
 [lsv]: #Tags "LinuxServer.io build available"
 [alp]: #Tags "Base available: Linux Alpine"
 [deb]: #Tags "Base available: Debian"
 [ubu]: #Tags "Base available: Ubuntu"
 [ngx]: #Tags "Can run on Nginx"
 [apc]: #Tags "Can run on Apache"
 [py ]: #Tags "Python"
 [php]: #Tags "PHP Hypertext preprocessor"
 [jvm]: #Tags "Java"
 [tom]: #Tags "Tomcat"
 [gol]: #Tags "GoLang"
 [njs]: #Tags "NodeJs"
 [sql]: #Tags "mySQL"
 [sl3]: #Tags "sqLite3"
 [psg]: #Tags "PostGre"

| Family           | Candicate           | Tags                              |   Arch. | Ports       | Notes |
| ---------------- | ------------------- | --------------------------------- | ------: | ----------- | ----- |
| [Automatization] | **[Drone]**         | [ofc], [gol]                      | [a] [6] | 80          |
| [Automatization] | **[Jenkins]**       | [ofc], [alp], [jvm]               |     [*] | 8080, 50000 |
| [Blog]           | **[WordPress]**     | [ofc], [alp], [php], [sql]        |     [*] | 80          |
| [Blog]           | **[Ghost]**         | [ofc], [alp], [njs], [sql], [sl3] |     [*] | 2368        |
| [DataBase]       | **[MariaDB]**       | [ofc], [lsv], [ubu]               | [a] [6] | 3306        |
| [DataBase]       | **[Postgres]**      | [ofc], [alp]                      |     [*] | 5432        |
| [DataBase]       | **[Redis]**         | [ofc], [alp]                      |     [*] | 6379        |
| [DataBase]       | **[ElasticSearch]** | [ofc], [alp], [jvm]               |     [X] |
| [DockerAdmin]    | **[Taisun]**        | [alp]                             | [a] [6] |
| [Domotics]       | **[Domoticz]**      |                                   | [a] [6] |
| **InProgress**   |
| [ERP]            | **[Clarkson]**      |                                   | [a] [6] |
| [ERP]            | **[Grocy]**         | [php], [alp], [ngx]               | [a] [6] |
| [ERP]            | **[Snipe-IT]**      | [alp], [php]                      | [a] [6] |
| [Git]            | **[Gogs]**          | [sql], [sl3], [psg]               |         |
| [Library]        | **[Calibre-Web]**   | [py]                              | [a] [6] |
| [Library]        | **[Ubooquity]**     |                                   | [a] [6] |
| [Metrics]        | **[Prometheus]**    |                                   |         |
| [Metrics]        | **[Grafana]**       |                                   |         |
| [Multimedia]     | **[Plex]**          | [ubu]                             |         |
| [Multimedia]     | **[Libresonic]**    | [lsv], [jvm]                      | [a] [6] |
| [Multimedia]     | **[Beets]**         |                                   | [a] [6] |
| [Others]         | **[Draw-io]**       | [alp], [tom]                      |         |
| [Others]         | **[GazeboSim]**     | [deb], [ubu]                      |         |
| [Photo]          | **[Piwigo]**        | [lsv], [alp], [php]               | [a] [6] |
| [Photo]          | **[Lychee]**        | [lsv], [alp], [php]               | [a] [6] |
| [Photo]          | **[PhotoShow]**     | [lsv], [alp], [php]               | [a] [6] |
| [RSS]            | **[Tt-rss]**        | [lsv], [alp], [php]               | [a] [6] |
| [RSS]            | **[FreshRSS]**      | [lsv], [alp], [php]               | [a] [6] |
| [ServiceHub]     | **[Organizr]**      | [lsv], [alp], [php]               | [a] [6] |
| [ServiceHub]     | **[Heimdall]**      |                                   | [a] [6] |
| [SyncBox]        | **[Pydio]**         | [lsv], [alp], [php]               | [a] [6] |
| [SyncBox]        | **[NextClud]**      | [php]                             |         |
| [SyncBox]        | **[OwnCloud]**      | [php]                             |         |
| [SyncBox]        | **[SyncThing]**     |                                   |         |
| [Onion]          | **[Tor]**           |                                   |         |
| [Torrent]        | **[Transmision]**   | [alp]                             |         |
| [VPN]            | **[OpenVpn]**       |                                   |     [y] |
| [WebServer]      | **[Nginx]**         | [alp]                             |         |
| [WebServer]      | **[Httpd]**         | [alp]                             |         |
| [Wiki]           | **[BookStak]**      | [lsv], [alp], [php]               | [a] [6] |
| [Wiki]           | **[MediaWiki]**     | [php], [sql]                      |         |

### Archs

|   #   |       x86-32       |       x86-64       |       armhf        |       arm64        |
| :---: | :----------------: | :----------------: | :----------------: | :----------------: |
|  [x]  | :heavy_check_mark: |                    |                    |                    |
|  [y]  |                    | :heavy_check_mark: |                    |                    |
|  [a]  |                    |                    | :heavy_check_mark: |                    |
|  [r]  |                    |                    |                    | :heavy_check_mark: |
|  [3]  | :heavy_check_mark: |                    | :heavy_check_mark: |                    |
|  [6]  |                    | :heavy_check_mark: |                    | :heavy_check_mark: |
|  [*]  | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |

 [x]: #Archs "x86-32"
 [y]: #Archs "x86-64"
 [a]: #Archs "armhf 32"
 [r]: #Archs "arm64"
 [3]: #Archs "all x32"
 [6]: #Archs "all x64"
 [*]: #Archs "all archs"

## Description

### Drone

>Drone is a Continuous Delivery platform that helps your organization optimize and automate software delivery. |
>
> [Home][drone_h] | [Docker Hub][drone_dh] | [Source][drone_src] | [Doc][drone_doc] || [Back](#Pieces)

[Drone]: #Drone
[drone_h]: https://drone.io/
[drone_dh]: https://hub.docker.com/r/drone/drone
[drone_src]: https://github.com/drone/drone
[drone_doc]: https://docs.drone.io/
[drone_logo]: https://docs.drone.io/favicon-32x32.png

### Jenkins

> Jenkins is a self-contained, open source automation server which can be used to automate all sorts of tasks related to building, testing, and delivering or deploying software.
>
> Jenkins can be installed through native system packages, Docker, or even run standalone by any machine with a Java Runtime Environment (JRE) installed.
>
> [Home][jenkins_h] | [Docker Hub][jenkins_dh] | [Source][jenkins_src] | [Doc][jenkins_doc] || [Back](#Pieces)

[Jenkins]: #Jenkins
[jenkins_h]: https://jenkins.io/
[jenkins_dh]: https://hub.docker.com/r/jenkins/jenkins
[jenkins_src]: https://github.com/jenkinsci
[jenkins_doc]: https://jenkins.io/doc/
[jenkins_logo]: https://jenkins.io/images/logos/general/256.png

### WordPress

> WordPress is a free and open source blogging tool and a content management system (CMS) based on PHP and MySQL, which runs on a web hosting service. Features include a plugin architecture and a template system. WordPress is used by more than 22.0% of the top 10 million websites as of August 2013. WordPress is the most popular blogging system in use on the Web, at more than 60 million websites. The most popular languages used are English, Spanish and Bahasa Indonesia.
>
> [Home][wp_h] | [Docker Hub][wp_dh] | [Source][wp_src] || [Back](#Pieces)

[WordPress]: #WordPress
[wp_h]: https://wordpress.org/
[wp_dh]: https://hub.docker.com/_/wordpress
[wp_src]: https://core.trac.wordpress.org/browser
[wp_doc]: #
[wp_logo]: https://d1q6f0aelx0por.cloudfront.net/product-logos/fcbd05b8-ec7e-4191-80f6-dae8ec3d9d25-wordpress.png

### Ghost

> Ghost is a free and open source blogging platform written in JavaScript and distributed under the MIT License, designed to simplify the process of online publishing for individual bloggers as well as online publications.
>
> [Home][ghost_h] | [Docker Hub][ghost_dh] | [Doc][ghost_doc] || [Back](#Pieces)

[Ghost]: #Ghost
[ghost_h]: https://ghost.org
[ghost_dh]: https://hub.docker.com/_/ghost
[ghost_src]: #
[ghost_doc]: https://docs.ghost.org/concepts/introduction/

### MariaDb

> MariaDB is a community-developed fork of the MySQL relational database management system intended to remain free under the GNU GPL. Being a fork of a leading open source software system, it is notable for being led by the original developers of MySQL, who forked it due to concerns over its acquisition by Oracle. Contributors are required to share their copyright with the MariaDB Foundation.
>
> The intent is also to maintain high compatibility with MySQL, ensuring a "drop-in" replacement capability with library binary equivalency and exact matching with MySQL APIs and commands. It includes the XtraDB storage engine for replacing InnoDB, as well as a new storage engine, Aria, that intends to be both a transactional and non-transactional engine perhaps even included in future versions of MySQL.
>
> [Home][maria_h] | [Docker Hub][maria_dh]| [LinuxServer.io][maria_lsi] | [Source][maria_src] | [Doc][maria_doc] || [Back](#Pieces)

[MariaDb]: #MariaDb
[maria_h]: https://mariadb.org/
[maria_dh]: https://hub.docker.com/_/mariadb
[maria_lsi]: https://github.com/linuxserver/docker-mariadb
[maria_src]: https://github.com/MariaDB
[maria_doc]: https://mariadb.org/learn/
[maria_logo]: https://d1q6f0aelx0por.cloudfront.net/product-logos/d8cef0f8-8a8f-4d8f-8efb-e6d40560fc82-mariadb.png?

### Postgres

> PostgreSQL is an object-relational database management system (ORDBMS) with an emphasis on extensibility and standards-compliance. As a database server, its primary function is to store data, securely and supporting best practices, and retrieve it later, as requested by other software applications, be it those on the same computer or those running on another computer across a network (including the Internet). It can handle workloads ranging from small single-machine applications to large Internet-facing applications with many concurrent users. Recent versions also provide replication of the database itself for security and scalability.
>
> PostgreSQL implements the majority of the SQL:2011 standard, is ACID-compliant and transactional (including most DDL statements) avoiding locking issues using multiversion concurrency control (MVCC), provides immunity to dirty reads and full serializability; handles complex SQL queries using many indexing methods that are not available in other databases; has updateable views and materialized views, triggers, foreign keys; supports functions and stored procedures, and other expandability, and has a large number of extensions written by third parties. In addition to the possibility of working with the major proprietary and open source databases, PostgreSQL supports migration from them, by its extensive standard SQL support and available migration tools. And if proprietary extensions had been used, by its extensibility that can emulate many through some built-in and third-party open source compatibility extensions, such as for Oracle.
>
> [Home][postgres_h] | [Docker Hub][postgres_dh] | [Source][postgres_src] | [Doc][postgres_doc] || [Back](#Pieces)

[Postgres]: #Postgres
[postgres_h]: https://www.postgresql.org/
[postgres_dh]: https://hub.docker.com/_/postgres
[postgres_src]: https://git.postgresql.org/gitweb/?p=postgresql.git
[postgres_doc]: https://www.postgresql.org/docs/

### Redis

> Redis is an open-source, networked, in-memory, key-value data store with optional durability. It is written in ANSI C. The development of Redis is sponsored by Redis Labs today; before that, it was sponsored by Pivotal and VMware. According to the monthly ranking by DB-Engines.com, Redis is the most popular key-value store. The name Redis means REmote DIctionary Server.
>
> [Home][redis_h] | [Docker Hub][redis_dh] | [Source][redis_src] | [Doc][redis_doc] || [Back](#Pieces)

[Redis]: #Redis
[redis_h]: https://redis.io/
[redis_dh]: https://hub.docker.com/_/redis
[redis_src]: #
[redis_doc]: #

### ElasticSearch

> info
>
> [Home][<tag>_h] | [Docker Hub][<tag>_dh] | [Source][<tag>_src] | [Doc][<tag>_doc] || [Back](#Pieces)

[ElasticSearch]: #ElasticSearch
[<tag>_h]: https://#
[<tag>_dh]: https://hub.docker.com/_/elasticsearch
[<tag>_src]: https://#
[<tag>_doc]: https://#
[<tag>_logo]: https://#

### Taisun

> Taisun is an application for a Docker enabled device with an emphasis on providing a web based interface for managing a single server. Taisun allows you to:
>
> Deploy and manage web based virtual desktops.
>
> Deploy Taisun specific stacks of applications
>
> Browse available images on popular Docker repositories
>
> Import a Docker project from any git repository and start developing on your choice of web based IDE or full Linux desktop
>
> Spinup a developer container based on popular frameworks and work from a web based IDE
>
> Single click remote server access to Taisun and your Docker applications
>
> [Home][taisun_h] | [Docker Hub][taisun_dh] | [Source][taisun_src] | [Doc][taisun_doc] || [Back](#Pieces)

[Taisun]: #Taisun
[taisun_h]: https://www.taisun.io/
[taisun_dh]: https://github.com/linuxserver/docker-taisun
[taisun_src]: https://github.com/Taisun-Docker/taisun
[taisun_doc]: #

### Domoticz

> Domoticz is a Home Automation System that lets you monitor and configure various devices like: Lights, Switches, various sensors/meters like Temperature, Rain, Wind, UV, Electra, Gas, Water and much more. Notifications/Alerts can be sent to any mobile device.
>
> [Home][domoticz_h] | [Docker Hub][domoticz_dh] | [Source][domoticz_src] | [Doc][domoticz_doc] || [Back](#Pieces)

[Domoticz]: #Domoticz
[domoticz_h]: https://www.domoticz.com/
[domoticz_dh]: https://github.com/linuxserver/docker-domoticz
[domoticz_src]: https://github.com/domoticz/domoticz
[domoticz_doc]: #
# Yolks

A curated collection of core images that can be used with Pterodactyl's Egg system. Each image is rebuilt
periodically to ensure dependencies are always up-to-date.

Images are hosted on `ghcr.io` and exist under the `games`, `installers`, and `yolks` spaces. The following logic
is used when determining which space an image will live under:

* `games` — anything within the `games` folder in the repository. These are images built for running a specific game
or type of game.
* `installers` — anything living within the `installers` directory. These images are used by install scripts for different
Eggs within Pterodactyl, not for actually running a game server. These images are only designed to reduce installation time
and network usage by pre-installing common installation dependencies such as `curl` and `wget`.
* `yolks` — these are more generic images that allow different types of games or scripts to run. They're generally just
a specific version of software and allow different Eggs within Pterodactyl to switch out the underlying implementation. An
example of this would be something like Java or Python which are used for running bots, Minecraft servers, etc.

All of these images are available for `linux/amd64` and `linux/arm64` versions, unless otherwise specified, to use
these images on an arm system, no modification to them or the tag is needed, they should just work.

## Available Images

### [Oses](/oses)

* [alpine](/oses/alpine)
  * `ghrc.io/andyondrya/yolks:alpine`
* [debian](/oses/debian)
  * `ghrc.io/andyondrya/yolks:debian`
* [ubuntu](/oses/ubuntu)
  * `ghrc.io/andyondrya/yolks:ubuntu`

### [Golang](/go)

* [`go1.14`](/go/1.14)
  * `ghrc.io/andyondrya/yolks:go_1.14`
* [`go1.15`](/go/1.15)
  * `ghrc.io/andyondrya/yolks:go_1.15`
* [`go1.16`](/go/1.16)
  * `ghrc.io/andyondrya/yolks:go_1.16`
* [`go1.17`](/go/1.17)
  * `ghrc.io/andyondrya/yolks:go_1.17`
* [`go1.18`](/go/1.18)
  * `ghrc.io/andyondrya/yolks:go_1.18`
* [`go1.19`](/go/1.19)
  * `ghrc.io/andyondrya/yolks:go_1.19`
* [`go1.20`](/go/1.20)
  * `ghrc.io/andyondrya/yolks:go_1.20`
* [`go1.21`](/go/1.21)
  * `ghrc.io/andyondrya/yolks:go_1.21`
* [`go1.22`](/go/1.22)
  * `ghrc.io/andyondrya/yolks:go_1.22`
* [`go1.23`](/go/1.23)
  * `ghrc.io/andyondrya/yolks:go_1.23`
* [`go1.24`](/go/1.24)
  * `ghrc.io/andyondrya/yolks:go_1.24`
  
### [Java](/java)

* [`java8`](/java/8)
  * `ghrc.io/andyondrya/yolks:java_8`
* [`java11`](/java/11)
  * `ghrc.io/andyondrya/yolks:java_11`
* [`java16`](/java/16)
  * `ghrc.io/andyondrya/yolks:java_16`
* [`java17`](/java/17)
  * `ghrc.io/andyondrya/yolks:java_17`
* [`java19`](/java/19)
  * `ghrc.io/andyondrya/yolks:java_19`
* [`java21`](/java/21)
  * `ghrc.io/andyondrya/yolks:java_21`
* [`java22`](/java/22)
  * `ghrc.io/andyondrya/yolks:java_22`
* [`java25`](/java/25)
  * `ghrc.io/andyondrya/yolks:java_25`

### [MariaDB](/mariadb)

  * [`MariaDB 10.3`](/mariadb/10.3)
    * `ghrc.io/andyondrya/yolks:mariadb_10.3`
  * [`MariaDB 10.4`](/mariadb/10.4)
    * `ghrc.io/andyondrya/yolks:mariadb_10.4`
  * [`MariaDB 10.5`](/mariadb/10.5)
    * `ghrc.io/andyondrya/yolks:mariadb_10.5`
  * [`MariaDB 10.6`](/mariadb/10.6)
    * `ghrc.io/andyondrya/yolks:mariadb_10.6`
  * [`MariaDB 10.7`](/mariadb/10.7)
    * `ghrc.io/andyondrya/yolks:mariadb_10.7`
  * [`MariaDB 11.2`](/mariadb/11.2)
    * `ghrc.io/andyondrya/yolks:mariadb_11.2`
  * [`MariaDB 11.3`](/mariadb/11.3)
    * `ghrc.io/andyondrya/yolks:mariadb_11.3`
  * [`MariaDB 11.4`](/mariadb/11.4)
    * `ghrc.io/andyondrya/yolks:mariadb_11.4`
  * [`MariaDB 11.5`](/mariadb/11.5)
    * `ghrc.io/andyondrya/yolks:mariadb_11.5`
  * [`MariaDB 11.6`](/mariadb/11.6)
    * `ghrc.io/andyondrya/yolks:mariadb_11.6`

### [MongoDB](/mongodb)

  * [`MongoDB 5`](/mongodb/5)
    * `ghrc.io/andyondrya/yolks:mongodb_5`
 * [`MongoDB 6`](/mongodb/6)
    * `ghrc.io/andyondrya/yolks:mongodb_6`    
 * [`MongoDB 7`](/mongodb/7)
    * `ghrc.io/andyondrya/yolks:mongodb_7`
 * [`MongoDB 8`](/mongodb/8)
    * `ghrc.io/andyondrya/yolks:mongodb_8` 

### [Nodejs](/nodejs)

* [`node12`](/nodejs/12)
  * `ghrc.io/andyondrya/yolks:nodejs_12`
* [`node14`](/nodejs/14)
  * `ghrc.io/andyondrya/yolks:nodejs_14`
* [`node16`](/nodejs/16)
  * `ghrc.io/andyondrya/yolks:nodejs_16`
* [`node17`](/nodejs/17)
  * `ghrc.io/andyondrya/yolks:nodejs_17`
* [`node18`](/nodejs/18)
  * `ghrc.io/andyondrya/yolks:nodejs_18`
* [`node19`](/nodejs/19)
  * `ghrc.io/andyondrya/yolks:nodejs_19`
* [`node20`](/nodejs/20)
  * `ghrc.io/andyondrya/yolks:nodejs_20`
* [`node21`](/nodejs/21)
  * `ghrc.io/andyondrya/yolks:nodejs_21`
* [`node22`](/nodejs/22)
  * `ghrc.io/andyondrya/yolks:nodejs_22`  
* [`node23`](/nodejs/23)
  * `ghrc.io/andyondrya/yolks:nodejs_23`
* [`node24`](/nodejs/24)
  * `ghrc.io/andyondrya/yolks:nodejs_24`  
  
### [PostgreSQL](/postgres)

  * [`Postgres 9`](/postgres/9)
    * `ghrc.io/andyondrya/yolks:postgres_9`
  * [`Postgres 10`](/postgres/10)
    * `ghrc.io/andyondrya/yolks:postgres_10`
  * [`Postgres 11`](/postgres/11)
    * `ghrc.io/andyondrya/yolks:postgres_11`
  * [`Postgres 12`](/postgres/12)
    * `ghrc.io/andyondrya/yolks:postgres_12`
  * [`Postgres 13`](/postgres/13)
    * `ghrc.io/andyondrya/yolks:postgres_13`
  * [`Postgres 14`](/postgres/14)
    * `ghrc.io/andyondrya/yolks:postgres_14`  

### [Python](/python)

* [`python3.7`](/python/3.7)
  * `ghrc.io/andyondrya/yolks:python_3.7`
* [`python3.8`](/python/3.8)
  * `ghrc.io/andyondrya/yolks:python_3.8`
* [`python3.9`](/python/3.9)
  * `ghrc.io/andyondrya/yolks:python_3.9`
* [`python3.10`](/python/3.10)
  * `ghrc.io/andyondrya/yolks:python_3.10`
* [`python3.11`](/python/3.11)
  * `ghrc.io/andyondrya/yolks:python_3.11`
* [`python3.12`](/python/3.12)
  * `ghrc.io/andyondrya/yolks:python_3.12`
* [`python3.13`](/python/3.13)
  * `ghrc.io/andyondrya/yolks:python_3.13`

### [Redis](/redis)

  * [`Redis 5`](/redis/5)
    * `ghrc.io/andyondrya/yolks:redis_5`
  * [`Redis 6`](/redis/6)
    * `ghrc.io/andyondrya/yolks:redis_6`
  * [`Redis 7`](/redis/7)
    * `ghrc.io/andyondrya/yolks:redis_7`
  * [`Redis 8`](/redis/8)
    * `ghrc.io/andyondrya/yolks:redis_8`    

### [Installation Images](/installers)

* [`alpine-install`](/installers/alpine)
  * `ghrc.io/andyondrya/installers:alpine`
* [`debian-install`](/installers/debian)
  * `ghrc.io/andyondrya/installers:debian`
* [`ubuntu-install`](/installers/ubuntu)
  * `ghrc.io/andyondrya/installers:ubuntu`

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
  * `ghcr.io/ondryadev/yolks:alpine`
* [debian](/oses/debian)
  * `ghcr.io/ondryadev/yolks:debian`
* [ubuntu](/oses/ubuntu)
  * `ghcr.io/ondryadev/yolks:ubuntu`

### [Golang](/go)

* [`go1.14`](/go/1.14)
  * `ghcr.io/ondryadev/yolks:go_1.14`
* [`go1.15`](/go/1.15)
  * `ghcr.io/ondryadev/yolks:go_1.15`
* [`go1.16`](/go/1.16)
  * `ghcr.io/ondryadev/yolks:go_1.16`
* [`go1.17`](/go/1.17)
  * `ghcr.io/ondryadev/yolks:go_1.17`
* [`go1.18`](/go/1.18)
  * `ghcr.io/ondryadev/yolks:go_1.18`
* [`go1.19`](/go/1.19)
  * `ghcr.io/ondryadev/yolks:go_1.19`
* [`go1.20`](/go/1.20)
  * `ghcr.io/ondryadev/yolks:go_1.20`
* [`go1.21`](/go/1.21)
  * `ghcr.io/ondryadev/yolks:go_1.21`
* [`go1.22`](/go/1.22)
  * `ghcr.io/ondryadev/yolks:go_1.22`
* [`go1.23`](/go/1.23)
  * `ghcr.io/ondryadev/yolks:go_1.23`

### [Java](/java)

* [`java8`](/java/8)
  * `ghcr.io/ondryadev/yolks:java_8`
* [`java11`](/java/11)
  * `ghcr.io/ondryadev/yolks:java_11`
* [`java16`](/java/16)
  * `ghcr.io/ondryadev/yolks:java_16`
* [`java17`](/java/17)
  * `ghcr.io/ondryadev/yolks:java_17`
* [`java19`](/java/19)
  * `ghcr.io/ondryadev/yolks:java_19`
* [`java21`](/java/21)
  * `ghcr.io/ondryadev/yolks:java_21`
* [`java22`](/java/22)
  * `ghcr.io/ondryadev/yolks:java_22`
* [`java25`](/java/25)
  * `ghcr.io/ondryadev/yolks:java_25`

### [MariaDB](/mariadb)

  * [`MariaDB 10.3`](/mariadb/10.3)
    * `ghcr.io/ondryadev/yolks:mariadb_10.3`
  * [`MariaDB 10.4`](/mariadb/10.4)
    * `ghcr.io/ondryadev/yolks:mariadb_10.4`
  * [`MariaDB 10.5`](/mariadb/10.5)
    * `ghcr.io/ondryadev/yolks:mariadb_10.5`
  * [`MariaDB 10.6`](/mariadb/10.6)
    * `ghcr.io/ondryadev/yolks:mariadb_10.6`
  * [`MariaDB 10.7`](/mariadb/10.7)
    * `ghcr.io/ondryadev/yolks:mariadb_10.7`
  * [`MariaDB 11.2`](/mariadb/11.2)
    * `ghcr.io/ondryadev/yolks:mariadb_11.2`
  * [`MariaDB 11.3`](/mariadb/11.3)
    * `ghcr.io/ondryadev/yolks:mariadb_11.3`
  * [`MariaDB 11.4`](/mariadb/11.4)
    * `ghcr.io/ondryadev/yolks:mariadb_11.4`
  * [`MariaDB 11.5`](/mariadb/11.5)
    * `ghcr.io/ondryadev/yolks:mariadb_11.5`
  * [`MariaDB 11.6`](/mariadb/11.6)
    * `ghcr.io/ondryadev/yolks:mariadb_11.6`

### [MongoDB](/mongodb)

  * [`MongoDB 5`](/mongodb/5)
    * `ghcr.io/ondryadev/yolks:mongodb_5`
 * [`MongoDB 6`](/mongodb/6)
    * `ghcr.io/ondryadev/yolks:mongodb_6`    
 * [`MongoDB 7`](/mongodb/7)
    * `ghcr.io/ondryadev/yolks:mongodb_7`
 * [`MongoDB 8`](/mongodb/8)
    * `ghcr.io/ondryadev/yolks:mongodb_8` 

### [Nodejs](/nodejs)

* [`node12`](/nodejs/12)
  * `ghcr.io/ondryadev/yolks:nodejs_12`
* [`node14`](/nodejs/14)
  * `ghcr.io/ondryadev/yolks:nodejs_14`
* [`node16`](/nodejs/16)
  * `ghcr.io/ondryadev/yolks:nodejs_16`
* [`node17`](/nodejs/17)
  * `ghcr.io/ondryadev/yolks:nodejs_17`
* [`node18`](/nodejs/18)
  * `ghcr.io/ondryadev/yolks:nodejs_18`
* [`node19`](/nodejs/19)
  * `ghcr.io/ondryadev/yolks:nodejs_19`
* [`node20`](/nodejs/20)
  * `ghcr.io/ondryadev/yolks:nodejs_20`
* [`node21`](/nodejs/21)
  * `ghcr.io/ondryadev/yolks:nodejs_21`
* [`node22`](/nodejs/22)
  * `ghcr.io/ondryadev/yolks:nodejs_22`  
* [`node23`](/nodejs/23)
  * `ghcr.io/ondryadev/yolks:nodejs_23`
* [`node24`](/nodejs/24)
  * `ghcr.io/ondryadev/yolks:nodejs_24`  
  
### [PostgreSQL](/postgres)

  * [`Postgres 9`](/postgres/9)
    * `ghcr.io/ondryadev/yolks:postgres_9`
  * [`Postgres 10`](/postgres/10)
    * `ghcr.io/ondryadev/yolks:postgres_10`
  * [`Postgres 11`](/postgres/11)
    * `ghcr.io/ondryadev/yolks:postgres_11`
  * [`Postgres 12`](/postgres/12)
    * `ghcr.io/ondryadev/yolks:postgres_12`
  * [`Postgres 13`](/postgres/13)
    * `ghcr.io/ondryadev/yolks:postgres_13`
  * [`Postgres 14`](/postgres/14)
    * `ghcr.io/ondryadev/yolks:postgres_14`  

### [Python](/python)

* [`python3.7`](/python/3.7)
  * `ghcr.io/ondryadev/yolks:python_3.7`
* [`python3.8`](/python/3.8)
  * `ghcr.io/ondryadev/yolks:python_3.8`
* [`python3.9`](/python/3.9)
  * `ghcr.io/ondryadev/yolks:python_3.9`
* [`python3.10`](/python/3.10)
  * `ghcr.io/ondryadev/yolks:python_3.10`
* [`python3.11`](/python/3.11)
  * `ghcr.io/ondryadev/yolks:python_3.11`
* [`python3.12`](/python/3.12)
  * `ghcr.io/ondryadev/yolks:python_3.12`
* [`python3.13`](/python/3.13)
  * `ghcr.io/ondryadev/yolks:python_3.13`

### [Redis](/redis)

  * [`Redis 5`](/redis/5)
    * `ghcr.io/ondryadev/yolks:redis_5`
  * [`Redis 6`](/redis/6)
    * `ghcr.io/ondryadev/yolks:redis_6`
  * [`Redis 7`](/redis/7)
    * `ghcr.io/ondryadev/yolks:redis_7`
  * [`Redis 8`](/redis/8)
    * `ghcr.io/ondryadev/yolks:redis_8`    

### [Installation Images](/installers)

* [`alpine-install`](/installers/alpine)
  * `ghcr.io/ondryadev/installers:alpine`
* [`debian-install`](/installers/debian)
  * `ghcr.io/ondryadev/installers:debian`
* [`ubuntu-install`](/installers/ubuntu)
  * `ghcr.io/ondryadev/installers:ubuntu`

# PHP-FPM 5.3

**Available Architectures:**  `amd64`, `arm64`

This repository will provide you a fully functional PHP-FPM 5.3 Docker image built from [official sources](http://museum.php.net) nightly. Additional patches have been applied to enable FPM functionality. PHP 5.3 [reached EOL](https://secure.php.net/eol.php) on 14 Aug 2014 and thus, official docker support was dropped. It provides the base for [LinuxEye PHP-FPM Docker images](https://github.com/linuxeye/docker-php-fpm).

## 🐋 Available Docker tags

[![](https://img.shields.io/docker/pulls/bypanel/php-fpm-5.3.svg)](https://hub.docker.com/r/bypanel/php-fpm-5.3)

[`latest`][tag_latest] [`stretch`][tag_stretch]

```bash
docker pull bypanel/php-fpm-5.3
```

#### Rolling releases

The following Docker image tags are rolling releases and are built and updated every night.

| Docker Tag                  | Git Ref |  Available Architectures  |
|-----------------------------|---------|---------------------------|
| **[`latest`][tag_latest]**  |   main  |     `amd64`, `arm64`      |
| [`stretch`][tag_stretch]    |   main  |     `amd64`, `arm64`      |

[tag_latest]: https://github.com/linuxeye/docker-php-fpm-5.3/blob/main/Dockerfile.latest
[tag_stretch]: https://github.com/linuxeye/docker-php-fpm-5.3/blob/main/Dockerfile.stretch

**Findme:**
**🐱** [linuxeye](https://github.com/linuxeye)
**🐋** [bypanel](https://hub.docker.com/r/bypanel)

# bastille-traefik
Bastille template for running Traefik edge router in a FreeBSD jail

By default it installs the recent version of Traefik avilable in ports.

## Bootstrap

```shell
bastille bootstrap https://github.com/yaazkal/bastille-traefik
```

## Usage

Install latest version of postgresql-server

```shell
bastille template TARGET yaazkal/bastille-traefik
```

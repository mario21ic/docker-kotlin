# docker-kotlin

[![Docker Pulls](https://img.shields.io/docker/pulls/yongjhih/kotlin.svg?style=flat-square)](https://hub.docker.com/r/yongjhih/kotlin/)
[![Docker Stars](https://img.shields.io/docker/stars/yongjhih/kotlin.svg?style=flat-square)](https://hub.docker.com/r/yongjhih/kotlin/)
[![](https://badge.imagelayers.io/yongjhih/kotlin.svg)](https://imagelayers.io/?images=yongjhih/kotlin:latest 'Get your own badge on imagelayers.io')

## Usage

kotlin script for jvm

```sh
docker-kotlin kotlinc-jvm -script HelloWorld.kts
```

kotlin script for js

```sh
docker-kotlin kotlinc-js -output index.js -meta-info index.kt
```

## ref

* https://kotlinlang.org/docs/tutorials/command-line.html
* https://kotlinlang.org/docs/tutorials/command-line-library-js.html


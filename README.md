# docker-ruby-golang
- [`1.6.2` (Dockerfile*)](https://github.com/InWork/docker-ruby-golang/blob/a595462c12b7e5dbdcb65797c7565dd8ed69b90e/Dockerfile)

[![](https://imagelayers.io/badge/inwork/docker-ruby-golang:latest.svg)](https://imagelayers.io/?images=inwork/docker-ruby-golang:latest 'Get your own badge on imagelayers.io')

This docker image contains go (Golang) and ruby for build enviroment.
It is mainly use to build your go app in a gitlab-ci enviroment.

It is based on the docker offical ruby image.

## Additinal dev tools

* godep
* glide

# How to use this image

````
FROM inwork/docker-ruby-golang:1.6.2
````

# License

View [license information](http://golang.org/LICENSE) for the golang contained in this image.
View [license information](https://www.ruby-lang.org/en/about/license.txt) for the ruby contained in this image.
View [license information](https://github.com/tools/godep/blob/master/License) for the godep contained in this image.
View [license information](https://github.com/Masterminds/glide/blob/master/LICENSE) for the glide contained in this image.

# BeagleKube
Small Beaglebone cluster with Kubernetes

## Why ?

I don't have any money to play with big tech clouds but I want to test some DevOps.

Moreover, big tech clouds are like MacDonald's playground : clean, secure, without creativity. You play this way or you out of it.

If you really want to learn how something works, you would want to take it apart, try to understand it, change things, break it, fix it. I want a sandbox, an open field, a grove, something open to creativity.

I've got a bunch of Beaglebone black so I devise I can create my own small cloud to play with it. It's not original, others have made it to.

Something like MiniKube is fine to learn the basic, but it's not like testing load and watching node crumble under it. Or devise a way to deploy efficiently Rust, WebAssembly or Elixir app without paying any money for my mistakes/learning.

It's just for my private usage. It won't even be connected to the internet.

## Goal

A small cluster of Beaglebone running Kubernetes on which deploy Docker containers and monitor it with Prometheus.

## Result

See [documentation](doc/README.md) for more information.

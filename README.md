WORMHOLE
========

Wormhole allows us to securely tunnel into our servers to test databases or web servers without having to open ports to the public.

To run it, clone the repo and just do the following:

```
cd THIS_REPO_DIRECTORY_WHEREVER_YOU_PUT_IT
sudo mv wormhole /usr/bin/wormhole OR stick it in your $PATH somewhere
```

To use it, you have the following options:

```
Either:
wormhole myserver #loads saved config and connects

Or:
wormhole [options]
  -s localhost e.g. myserver.com
  -u username e.g. jimbob
  -t target port e.g. 3000
  -i target interface e.g. 127.0.0.1
  -l local port e.g. 8091
  -r remember (saves settings) e.g. myserver
```
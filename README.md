# nc-shaddock
Node Computes Deployment (in Docker)

The current deployment tool for NC is Shaddock (http://github.com/epheo/shaddock)

This is an example of how to deploy NC in MacOS with Boot2Docker

```
❯❯❯ cd node-computes/nc-shaddock
❯❯❯ eval "$(sudo docker-machine env vb_name)"
❯❯❯ shaddock -f ./nc.yml -d ./images --boot2docker build all
❯❯❯ shaddock -f ./nc.yml -d ./images --boot2docker start all
```

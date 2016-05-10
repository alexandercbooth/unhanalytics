# Official Docker Image for UNHAnalytics
<img src="EmblemDigital_RGB.png" height=200>

[![DockerPulls](https://img.shields.io/docker/pulls/alexandercbooth/unhanalytics.svg)](https://registry.hub.docker.com/u/alexandercbooth/unhanalytics/)

To start a notebook, run:
```
docker run -it -p 8888:8888 alexandercbooth/unhanalytics jupyter notebook
```
Then go to localhost:8888/ if on linux or have docker beta. If on OSX or Windows, type docker info to find your IP and go to IP:8888.

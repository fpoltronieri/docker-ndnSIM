# docker-ndnSIM

A container for running ndnSIM.

```
docker build -t ndnsim .
```
Start the container with X forwarding enabled:

```
docker run -t -i -h ndn -e DISPLAY=$DISPLAY -v /tmp/.X11-unix/:/tmp/.X11-unix/ ndnsim
```

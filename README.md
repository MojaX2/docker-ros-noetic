# docker-ros-noetic

```bash
docker build . -t moja2/docker-ros-noetic
```

# sample
```
$ docker run -it --rm --net=host docker-ros-noetic roscore

$ docker run -it --rm --net=host docker-ros-noetic rosrun roscpp_tutorials talker

$ docker run -it --rm --net=host docker-ros-noetic rosrun roscpp_tutorials listener


```

http://wiki.ros.org/noetic

cuda 

https://hub.docker.com/r/vistart/cuda
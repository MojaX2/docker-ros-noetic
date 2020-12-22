# docker-ros-noetic

docker, ros, noetic, cuda, pytorch

```bash
docker build . -t moja2/docker-ros-noetic
```

# sample
```bash
$ docker run -it --rm --net=host moja2/docker-ros-noetic roscore

$ docker run -it --rm --net=host moja2/docker-ros-noetic rosrun roscpp_tutorials talker

$ docker run -it --rm --net=host moja2/docker-ros-noetic rosrun roscpp_tutorials listener
```

http://wiki.ros.org/noetic


https://ngc.nvidia.com/catalog/containers/nvidia:pytorch
#### Electrum windows build

Create unattended Tate Windows builds on Linux using docker.

##### Getting started


Clone this repository and run ./build 0.2 (or whatever the latest stable release is) and if
all goes well your windows binary should appear in the releases folder.

##### General remarks

There's a lot to apt-get in the Dockerfile, this will take a while to build 
the docker image. Once the docker image is built on your machine, the tate build 
runs quickly. 

This image is also available as an automated build on dockerhub

<code>git clone https://github.com/mazaclub/tate-winbuild && cd tate-winbuild
docker pull umazaclub/tate-winbuild
./build 0.2
</code>
Current image size is approximately 2.1GB 

* Only stable builds are supported so far, not building from git yet.

* Only the Standalone Executable is working so far.

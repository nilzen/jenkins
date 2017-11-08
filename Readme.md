# Jenkins CI LTS with Docker binaries

Automated Docker image build based on Jenkins CI LTS [jenkins/jenkins:lts](https://hub.docker.com/r/jenkins/jenkins/) with Docker binaries, to be able to build docker images directly on the master.

Mount Docker unix socket from the host to the container with `-v /var/run/docker.sock:/var/run/docker.sock`
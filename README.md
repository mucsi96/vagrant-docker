# vagrant-docker

If you would like to use [Docker](https://www.docker.com/) but you have no sucsess with [boot2docker](http://boot2docker.io/) try this as alternative. Boot2docker is based on Tiny Core Linux and I have problems with it. Also it does not support [docker-compose](https://docs.docker.com/compose/).

What if instead of Tiny Core Linux we will use Ubuntu 12.04 LTS (Precise)? And run it and provision with Docker and docker-compose using [Vagrant](https://www.vagrantup.com/).

Now we can use docker-compose on Mac and Windows.

## Prerequisites

- [Vagrant](https://www.vagrantup.com/)
- $ vagrant plugin install vagrant-reload

## Usage

    $ vagrant up
    $ vagrant ssh
    $ docker-compose

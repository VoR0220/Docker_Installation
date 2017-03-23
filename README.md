# Docker_Installation
Docker Installation for Ubuntu Linux


```
$ sudo apt-get install \
    apt-transport-https \
    ca-certificates \
    curl \
    software-properties-common
```

```
$ curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
```

```
sudo apt-get install docker-ce
```

```sudo start docker```

For OS X

```/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"```

```brew install caskroom/cask/brew-cask```

```
brew cask install virtualbox
brew install docker docker-machine

# create the vm
docker-machine create -d virtualbox dev

# import environment variables for the docker-cli
eval "$(docker-machine env dev)"

docker run hello-world
```


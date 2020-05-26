
# Example

|Stack |  Travis-CI  |
|:----:|:-----------:|
|Status| [![travisStatus](https://travis-ci.org/Sanny-Articles/article-example.svg?branch=master&status=passed)](https://travis-ci.org/github/Sanny-Articles/article-example)|

## Requirements

### Install texlive-full

```bash
sudo apt-get install texlive-full
```

### Install PCRE

```bash
sudo apt-get install libpcre3 libpcre3-dev
```

### Install Ruby

```bash
sudo apt update
sudo apt install curl g++ gcc autoconf automake bison libc6-dev \
        libffi-dev libgdbm-dev libncurses5-dev libsqlite3-dev libtool \
        libyaml-dev make pkg-config sqlite3 zlib1g-dev libgmp-dev \
        libreadline-dev libssl-dev
gpg --keyserver hkp://keys.gnupg.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3 7D2BAF1CF37B13E2069D6956105BD0E739499BDB
curl -sSL https://get.rvm.io | bash -s stable
source ~/.rvm/scripts/rvm
rvm install ruby
```

### Install Travis

```bash
gem install travis --no-document
```

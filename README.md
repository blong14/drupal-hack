# drupal-hack

## Installation

### Docker and Docker-Compose

Install [Docker For Mack](https://docs.docker.com/docker-for-mac/install/)

### Docker-Sync

`/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

`gem install docker-sync`

`brew install fswatch`

*There may be a couple of other things (unison?) to download for docker-sync but it should prompt you if anything is missing*

[reference](http://docs.docker4drupal.org/en/latest/macos/)

## Build & development

### Permissions

Initially, run `sudo dseditgroup -o edit -a $(id -un) -t user _clamav`

### Running the app

`docker-sync-stack start`

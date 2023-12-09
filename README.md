# docker-redmine-install

## Installation

### Linux

1. Install docker, docker-compose and git.
1. `$ git clone https://github.com/hiroaki-ma1203/docker-redmine-install.git`
1. `$ cd docker-redmine-install`
1. `$ docker-compose up -d`

### Add Redmine Plugins

1. `# cd /var/lib/docker/volumes/redmine-plugins/_data`
1. `# git clone https://github.com/XXXXXX/XXXXXX.git`
1. Go back to the `docker-redmine-install` directory.
1. `$ docker-compose restart`

### Add Redmine Themes

1. `# cd /var/lib/docker/volumes/redmine-themes/_data`
1. `# git clone https://github.com/XXXXXX/XXXXXX.git`
1. Go back to the `docker-redmine-install` directory.
1. `$ docker-compose restart`


## TODO

- How to auto backup.
- How to restore.
- How to update redmine and mysql.

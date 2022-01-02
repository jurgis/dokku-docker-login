# dokku-docker-login

dokku-docker-login is a plugin for [dokku][dokku] that gives the ability to deploy an application from a private docker registry.

## Installation

```bash
# dokku 0.4+
$ sudo dokku plugin:install https://github.com/jurgis/dokku-docker-login.git

# update the plugin
$ sudo dokku plugin:update docker-login
```

## Commands

```
$ dokku docker-login:help
    docker-login:report [<app>]                               Displays an docker-login report for one or more apps
    docker-login:reset <app>                                  Remove docker login information for the app
    docker-login:set <app> <username> <password> <registry>   Set docker login information for the app
    docker-login:show-config <app>                            Display docker-login config for the app
```

## Usage

TODO: ...

## License

This plugin is released under the MIT license. See the file [LICENSE](LICENSE).

[dokku]: https://github.com/dokku/dokku

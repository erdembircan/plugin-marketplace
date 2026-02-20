# erdembircan-plugins

A Claude Code plugin marketplace by Erdem Bircan.

## Plugins

### wordpress-docker

Set up a WordPress development environment using Docker with WP-CLI, MariaDB, and Xdebug.

- **Repository:** [erdembircan/wordpress-docker-plugin](https://github.com/erdembircan/wordpress-docker-plugin)
- **Version:** 1.0.0
- **Keywords:** wordpress, docker, wp-cli, mariadb, xdebug

### commit-push

Git commit and push with conventional commit messages.

- **Repository:** [erdembircan/commit-push-plugin](https://github.com/erdembircan/commit-push-plugin)
- **Version:** 1.0.0
- **Keywords:** git, commit, push, conventional-commits

### testing-philosophy

Enforces behavioral testing philosophy: test what code does for consumers, not how it works internally.

- **Repository:** [erdembircan/testing-philosophy-plugin](https://github.com/erdembircan/testing-philosophy-plugin)
- **Version:** 1.0.0
- **Keywords:** testing, philosophy, behavioral-testing, best-practices

## Installation

Add this marketplace to Claude Code:

```
/plugin marketplace add erdembircan/plugin-marketplace
```

Then install a plugin:

```
/plugin install wordpress-docker@erdembircan-plugins
/plugin install commit-push@erdembircan-plugins
/plugin install testing-philosophy@erdembircan-plugins
```

## License

This project is licensed under the [GNU Affero General Public License v3.0](LICENSE).

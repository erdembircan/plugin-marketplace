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

### usage-band

Shows the current session and weekly usage limits in a band above the prompt of the Claude desktop app, and locks a working session against Escape and stray prompts.

- **Repository:** [erdembircan/claude-usage-band](https://github.com/erdembircan/claude-usage-band)
- **Runs in:** the Claude desktop app
- **Keywords:** usage, rate-limits, desktop, session-lock, mod

### pipcast

Picture in picture for Claude Code. While you work in other apps, a small window in the corner of your Mac's screen shows a live board of your sessions, and cuts to BREAKING NEWS, the way a 1990s local TV station would, when one needs you, finishes or stops on an error. A small macOS app that comes with Pipcast runs the window, and nothing leaves your Mac.

- **Repository:** [erdembircan/pipcast](https://github.com/erdembircan/pipcast)
- **Runs in:** the Claude desktop app, on a Mac with Apple silicon and macOS 14 or later
- **Keywords:** picture-in-picture, pip, notifications, sessions, status, overlay, macos, mod

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
/plugin install usage-band@erdembircan-plugins
/plugin install pipcast@erdembircan-plugins
```

In the Claude desktop app, where `/plugin` doesn't run, click **+** next to the prompt box, then **Plugins**. Choose **Add marketplace**, enter `erdembircan/plugin-marketplace`, and add the plugin you want.

From a terminal, `claude plugin marketplace add erdembircan/plugin-marketplace` adds the marketplace, and `claude plugin install <plugin>@erdembircan-plugins` installs a plugin from it.

## License

This project is licensed under the [Apache License 2.0](LICENSE).

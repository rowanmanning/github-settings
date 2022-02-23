
# GitHub Settings

A shared GitHub settings config file for my projects.


## Table of Contents

  * [Usage](#usage)
  * [Contributing](#contributing)
  * [License](#license)


## Usage

The settings in [`.github/settings.yml`](.github/settings.yml) are synced using the [Probot Settings app](https://probot.github.io/apps/settings/). To use these consistent settings in a repo, create a `.github/settings.yml` file and add the following:

```sh
_extends: rowanmanning/github-settings
```

Then make sure the settings app is installed and monitoring the repo.


## Contributing

Genuinely unless you're Rowan Manning, you probably don't need to contribute to this. However if you decide you really need to, then [the contributing guide is available here](docs/contributing.md). All contributors must follow [this library's code of conduct](docs/code_of_conduct.md).


## License

Licensed under is licensed under the [MIT](LICENSE) license.<br/>
Copyright &copy; 2022, Rowan Manning

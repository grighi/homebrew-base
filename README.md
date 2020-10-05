
Forked and installed because brewsci/base still uses rstudio-server 1.2, which depends on openssl1.0, but I need openssl1.1 for other packages.

```
- forked randy3k/homebrew-base
- merged rstudio-server-1.3 to master so homebrew will see it
- tapped this repo, install from tap
```

# Brewsci/base

Science formulae for the [Linuxbrew](http://linuxbrew.sh) and [Homebrew](https://brew.sh) package managers.

## How do I install a formula?

```sh
brew tap brewsci/base
brew install FORMULA
```

or

```sh
brew install brewsci/base/FORMULA
```

## Commands

- **brew cite** Display citations of formulae and DOI

## Troubleshooting

First read the [Troubleshooting Checklist](http://docs.brew.sh/Troubleshooting.html).

Use `brew gist-logs FORMULA` to create a [Gist](https://gist.github.com/) and post the link in your issue.

Search the [issues](https://github.com/brewsci/homebrew-base/issues?q=). See also Homebrew's [Common Issues](https://docs.brew.sh/Common-Issues.html) and [FAQ](https://docs.brew.sh/FAQ.html).

## Documentation

`brew help`, `man brew`, or check [Homebrew's documentation](https://docs.brew.sh).

## Contributing

Please see the [contributing guide](https://github.com/brewsci/homebrew-base/blob/master/CONTRIBUTING.md).

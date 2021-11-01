# reposize

Find the size of a repository on Github from the command line.

## Install

Using homewbrew:
```shell
brew tap meowmeowmeowcat/taps
brew install meowmeowmeowcat/taps/reposize
```

Install manually:
```shell
curl -L https://raw.githubusercontent.com/meowmeowmeowcat/reposize/main/reposize \
  -o /usr/local/bin/reposize && chmod +x /usr/local/bin/reposize
```

## Usage

```shell
Usage: reposize <username/repository>
```

## Example

```shell
$ reposize meowmeowmeowcat/isarm
The size of repository 'meowmeowmeowcat/isarm' is 5 KB.
```


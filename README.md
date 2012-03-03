# resque-top

resque-top is a top-like command line utility to display resque queue and worker status, like [resque-web](https://github.com/defunkt/resque).

## Installation

### github

```
git clone git://github.com/miyagawa/resque-top.git
gem build resque-top.gemspec
gem install resque-top-<version>.gem
```

## Usage

```
resque-top -N <namespace> 
resque-top -r <hostname>:<port>/<namespace>
```

## Author

Tatsuhiko Miyagawa (@miyagawa)

## License

MIT License





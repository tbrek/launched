# Launched

A launchd.plist editor.

`launchd` is a powerful and flexible replacement for cron, but writing the plist
files for it by hand can be difficult. This app makes it easier.

YIBYABS: Yes, I Built Yet Another Bootstrap Site!

## Is it any good?

Yes.

## How to run locally
```bash
rvm install 1.9.3
git clone git@github.com:zerowidth/launched.git
cd Launched
brew install postgres
gem install bundler -v 1.17.0
bundle config build.eventmachine --with-cppflags=-I/usr/local/opt/openssl/include
bundle install
createuser -s launched
bundle exec rake db:setup
bundle exec rails server
```

## Contributing

* fork
* patch
* test
* pull request

## License

MIT, see `LICENSE`.

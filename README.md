# DTYoda Tap

Homebrew tap for [drop-zone](https://github.com/DTYoda/drop-zone), a peer-to-peer terminal file transfer client.

## Install

```sh
brew tap DTYoda/tap
brew install drop-zone
```

Or `brew install DTYoda/tap/drop-zone`.

In a `Brewfile`:

```ruby
tap "dtyoda/tap"
brew "drop-zone"
```

The formula builds only the client (`-DDZ_BUILD_SERVER=OFF`). After install, run `drop-zone setup`.

To follow `main` instead of the latest tag: `brew install --HEAD DTYoda/tap/drop-zone`.

## Documentation

`brew help`, `man brew` or [Homebrew's documentation](https://docs.brew.sh).

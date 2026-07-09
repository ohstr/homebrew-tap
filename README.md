# homebrew-tap

Homebrew tap for [`ncli`](https://github.com/ohstr/ncli), a single binary
for running and operating Nostr relays: serve, stream, sync, inspect,
search, export, and mine events.

## Usage

```sh
brew install ohstr/tap/ncli
```

or

```sh
brew tap ohstr/tap
brew install ncli
```

## About this repo

`Formula/ncli.rb` is generated and pushed automatically by
[GoReleaser](https://goreleaser.com) as part of `ncli`'s release workflow —
see the `brews:` section of
[`.goreleaser.yaml`](https://github.com/ohstr/ncli/blob/main/.goreleaser.yaml)
in the `ncli` repo. It is not meant to be hand-edited; any manual changes
will be overwritten on the next release.

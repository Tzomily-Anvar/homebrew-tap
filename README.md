# homebrew-tap

A Homebrew tap for [Argus](https://github.com/Tzomily-Anvar/argus).

```sh
brew install Tzomily-Anvar/tap/argus
```

Then:

```sh
argus setup     # answer a few questions
argus           # run it
```

## What is in here

One file, `Casks/argus.rb`, written by the release pipeline in the Argus
repository each time a version is tagged. It records the download URL and
SHA-256 of that release's macOS builds, and nothing else.

Nothing here is edited by hand. To change what the cask contains, change
`.goreleaser.yaml` in the Argus repository.

## Linux

Homebrew casks are macOS-only. On Linux, take the archive for your
architecture from the [releases
page](https://github.com/Tzomily-Anvar/argus/releases), or run the
container. Both are described in the Argus README.

## Licence

MIT, as Argus is.

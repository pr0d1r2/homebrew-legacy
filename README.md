# Homebrew Legacy

Legacy packages used in some projects.

## Why?
To have a following `Brewfile` possibility:

```
tap 'pr0d1r2/legacy'
brew 'elasticsearch@5.6', args: ['build-from-source']
```

## How do I install this formula?

Run `brew install pr0d1r2/legacy/elasticsearch@5.6 --build-from-source`.

Or `brew tap pr0d1r2/legacy` and then `brew install elasticsearch@5.6 --build-from-source`.

## Limitations
As unsupported packages do not have bottles we need to install from
source. This has been tested on macOS 10.13 so far.

## Documentation
`brew help`, `man brew` or check [Homebrew's documentation](https://docs.brew.sh).

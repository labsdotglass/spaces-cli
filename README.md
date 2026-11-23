# spaces

The command-line tool for [Spaces](https://joinspaces.ai): shared lists, notes, a cheat sheet and people for groups.
Every Spaces tool is a command, so you can use your spaces from a terminal, a script, CI or an agent.

This repository holds the releases. The source lives with the Spaces app.

## Install

```sh
brew install labsdotglass/spaces/spaces
```

Or download the archive for your system from [Releases](https://github.com/labsdotglass/spaces-cli/releases),
unpack it, and put `spaces` on your `PATH`. The binary is not signed yet. If you download it by hand on a Mac, run
`xattr -d com.apple.quarantine spaces` once.

## Use

```sh
spaces version
spaces auth login        # opens your browser to sign in to Spaces
spaces get-my-context    # your spaces
spaces --help            # every command
```

For scripts and CI, make a personal access token on your Account page in Spaces and set `SPACES_TOKEN`.

## Help

Write to support@joinspaces.ai.

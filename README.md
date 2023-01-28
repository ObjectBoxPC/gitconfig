# Personal Git Configuration

This the base of my personal Git configuration (`.gitconfig`) available for public use.

A large part of the configuration is a series of shortcut aliases for common operations. The most common operations are a single letter, such as `git a` for `git add` and `git h` for `git checkout`. Operations with additional options on the same Git command have additional letters attached to them, such as `git ap` for `git add -p`. Review the file for available aliases.

The remaining configuration establishes a useful baseline of common options, which you can adjust according to personal preference. For example, the style used for merge conflicts is set to diff3, which provides the contents of the common base of a conflict in addition to the two sides (this can help establish better context for the conflicting changes).

## Usage

Add the contents of this file to your user configuration file, located at `~/.gitconfig` (Unix-like systems, including Linux and macOS/OS X) or `%USERHOME%\.gitconfig` (Windows). Check for any duplicate settings and adjust as desired.

## License

The contents of the configuration file are dedicated to the public domain under [Creative Commons CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/). (A copy is available in `LICENSE.txt`.)

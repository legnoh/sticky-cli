# sticky

Simple script to import sticky with macOS Stickies.app!

## Install

```sh
brew install legnoh/etc/sticky-cli

# if your machine is not english, please set lang "en-US" to Stickies 
defaults write com.apple.Stickies AppleLanguages '("en-US")'
```

## Usage

```sh
sticky "/your/file/path.txt"
```

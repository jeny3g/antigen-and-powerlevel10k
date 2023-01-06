# Antigen and Powerlevel10k

This repository contains code for setting up Antigen and Powerlevel10k for configuring a custom terminal in macOS.

## What is Antigen?

Antigen is a small set of functions that help you easily manage your shell (zsh) configuration. It provides a set of defaults, such as adding the `~/.zshrc` file to your shell, along with some helpful functions. It also allows you to easily extend your configuration with plugins from a variety of sources.

## What is Powerlevel10k?

Powerlevel10k is a theme for the ZSH shell that provides a powerful and aesthetically pleasing experience. It comes with a set of customizable options that allow you to customize the look of your terminal.

## Installation

1. Clone this repository:

```
git clone https://github.com/jeny3g/antigen-and-powerlevel10k.git
```

2. Install Antigen:

```
curl -L git.io/antigen > antigen.zsh
```

3. Add the following to your `~/.zshrc` file:

```
source ~/antigen.zsh

# Load the antigen configuration
antigen bundle jeny3g/antigen-and-powerlevel10k

# Load the Powerlevel10k theme
source ~/powerlevel10k/powerlevel10k.zsh-theme
```

4. Reload your shell:

```
source ~/.zshrc
```

## Usage

Once installed, you can customize your terminal by editing the `~/.p10k.zsh` file.

## License

This repository is released under the MIT License. See the [LICENSE](LICENSE) file for more information.

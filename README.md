# My Termux Dotfiles
this repository holds my Termux dotfiles, aimed at boosting production and 

This repository holds my Termux dotfiles, aimed at boosting productivity and customizing the development experience on Android devices. The configurations cover essential tools like Git, Helix (text editor), and the Fish shell, alongside visual customizations and installation automation.

## 🚀 Highlights & Features
| Category                         | Description                                                                                                                             |
|----------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------|
| Essential Configurations         | Personalized setups for Git, Helix (default editor), and the Fish shell.                                                                |
| Development Environment          | Optimizations and configurations for languages like Rust, TypeScript, and Python. Includes support for language servers and formatters. |
| Visual Customization             | Management of fonts (e.g., IosevkaTermSlabNerdFontMono-Regular) and themes for an enhanced terminal visual experience.                  |
| Termux Properties                | Specific adjustments to Termux properties for environment optimization.                                                                 |
| Installation Automation          | A script to automate package and configuration installations.                                                                    |
| Terminal Cleanup                 | Automatic remove motd files located in $PREFIX/etc/motd*.                                                                               |

## 📦 Installation Guide
To set up your Termux environment with these definitions, follow the steps below:
 * Clone the Repository:
   Use Git to clone this repository to your home directory in Termux:
   `git clone https://github.com/rickferrdev/termux-dotfiles.git ~/dotfiles`

 * Execute the Installation Script:
   Navigate to the cloned directory and run the binary installation script:
   `./dotfiles/install`

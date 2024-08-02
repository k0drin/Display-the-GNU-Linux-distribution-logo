# Display Linux Distro Logo in Terminal

## Introduction
This guide will show you how to display your Linux distribution's logo in the terminal and ensure it appears each time you open a new terminal session.

### Install `neofetch`
neofetch is a popular tool that displays system information, including the Linux distribution logo, in the terminal.

#### Installation
**For Ubuntu/Debian**
```
sudo apt-get install neofetch
```
**For Arch Linux**
```
sudo pacman -S neofetch
```
**For Fedora**
```
sudo dnf install neofetch
```
**For openSUSE**
```
sudo zypper install neofetch
```

### Display the Logo Manually
To display the logo and system information manually, simply run
```
neofetch
```

### Automatically Display the Logo on Terminal Startup

To make `neofetch` run automatically each time you open a new terminal, you need to add it to your shell's configuration file.

**For bash**
1. Open your `.bashrc` file in a text editor
```
nano ~/.bashrc
```
2. Add the following line at the end of the file
```
neofetch
```
3. Save the file and exit the editor (`Ctrl+X`, then `Y` to confirm)

4. Apply the changes
```
source ~/.bashrc
```
**For zsh**
1. Open your `.zshrc` file in a text editor
```
nano ~/.zshrc
```
2. Add the following line at the end of the file
```
neofetch
```
3. Save the file and exit the editor (`Ctrl+X`, then `Y` to confirm)

4. Apply the changes
```
source ~/.zshrc
```
**For zsh**
1. Open your `config.fish` file in a text editor
```
nano ~/.config/fish/config.fish
```
2. Add the following line at the end of the file
```
neofetch
```
3. Save the file and exit the editor (`Ctrl+X`, then `Y` to confirm)

4. Apply the changes
```
source ~/.config/fish/config.fish
```

## Conclusion
You have now configured your terminal to display your Linux distribution's logo and system information each time you open a new terminal session. Enjoy your personalized terminal setup!
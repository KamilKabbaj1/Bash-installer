# bash-installer

A small Bash script that installs a package on a Debian/Ubuntu system (WSL included).

Made for the Git workflow exercise (part 11) of the course
"OOP & Design patterns in Python" (B. Dallard, CentraleSupélec).

## Usage

```bash
./install.sh
```

The script:

1. prints "Starting installation...",
2. refreshes the package lists (`sudo apt update`),
3. installs `tree` (`sudo apt install -y tree`),
4. prints "Installation complete!".

`sudo` asks for your password. The script stops at the first error (`set -e`).

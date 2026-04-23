# Get Started With Git & GitHub
Get started with Git, GitHub, and version control!

<i>Assuming you have a GitHub account; if not, create one!</i>

### --> Mac users:
1) Download Homebrew:
   -> Open Terminal
   -> /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   -> echo $PATH
   -> export PATH=$PATH:/opt/homebrew/bin
3) Install Git:
   -> brew install git
4) Install GitHub CLI (command-line interface):
   -> brew install gh
5) Log in to GitHub:
   -> gh auth login [choose HTTPS]

### --> Windows users:
1) Download Git:
   -> https://github.com/git-for-windows/git/releases/download/v2.54.0.windows.1/Git-2.54.0-64-bit.exe
2) Download GitHub CLI (command-line interface):
   -> https://github.com/cli/cli/releases/download/v2.91.0/gh_2.91.0_windows_amd64.msi
3) Log in to GitHub:
   -> gh auth login [choose HTTPS]

\
### Elementary "git" commands:
- git pull origin main
- git add .
- git commit -m "<MESSAGE>"
- git push -u origin main

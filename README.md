# Ideas
These look like they could be interesting:
https://github.com/grantjenks/free-python-games
To use this one, you should probably make a fork of it so you can have your own copy.  I can help you with this.  Then you can check out, make changes, and check them back in.

You can run a game like this:
python -m freegames.snake

This has less cues for what to change, but are pretty simple games and have better documentation on the coding concepts:
https://github.com/Ninedeadeyes/15-mini-python-games-tutorial-series

This actually looks really good (maybe the best of these since it starts really simple and builds).  We could make a new repository on your github account and you could just work through making the games that it shows here
https://inventwithpython.com/invent4thed/

# Downloading Git for Windows
Launch the terminal by typing "cmd" in the Windows run box.

Run this from the terminal
winget install --id Git.Git -e --source winget

# Clone a repo
git clone https://github.com/SammyBoy908/free-python-games.git
cd free-python-games


# How to Use Git
Check what files have edits, see what you need to add, etc

git status

## Making a Branch
C:\Users\grige\repos\free-python-games>git checkout -b sg/adding_basic_files
Switched to a new branch 'sg/adding_basic_files'

## Adding a file
git add <filename>

For instance
git add README.md

## Restoring a file
git restore --staged README.md

## Commit a file
git commit -m "My commit message"
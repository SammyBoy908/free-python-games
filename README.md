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

```
C:\Users\grige>f:
F:\>mkdir repos
F:\>cd repos
F:\repos>git clone https://github.com/SammyBoy908/free-python-games.git
Cloning into 'free-python-games'...
remote: Enumerating objects: 1658, done.
remote: Counting objects: 100% (1658/1658), done.
remote: Compressing objects: 100% (649/649), done.
remote: Total 1658 (delta 968), reused 1657 (delta 968), pack-reused 0 (from 0)
Receiving objects: 100% (1658/1658), 4.06 MiB | 7.58 MiB/s, done.
Resolving deltas: 100% (968/968), done.
Updating files: 100% (131/131), done.

F:\repos>

cd free-python-games
```

# Running a Game

```
F:\repos\free-python-games>pip install -e .
Obtaining file:///F:/repos/free-python-games
  Installing build dependencies ... done
  Checking if build backend supports build_editable ... done
  Getting requirements to build editable ... done
  Preparing editable metadata (pyproject.toml) ... done
Building wheels for collected packages: freegames
  Building editable for freegames (pyproject.toml) ... done
  Created wheel for freegames: filename=freegames-2.5.3-0.editable-py3-none-any.whl size=6574 sha256=96b738aa4d14084385acdf8a1771333200eea8044db1dadb055bb7e3d94dfd04
  Stored in directory: C:\Users\grige\AppData\Local\Temp\pip-ephem-wheel-cache-ra94osu4\wheels\55\3c\a3\60abd8c84768e8efb349c0da7e12949e9e8aecb4a06d7c198f
Successfully built freegames
Installing collected packages: freegames
  WARNING: The script freegames.exe is installed in 'C:\Users\grige\AppData\Local\Python\pythoncore-3.14-64\Scripts' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
Successfully installed freegames-2.5.3

[notice] A new release of pip is available: 26.0.1 -> 26.2.1
[notice] To update, run: C:\Users\grige\AppData\Local\Python\pythoncore-3.14-64\python.exe -m pip install --upgrade pip

F:\repos\free-python-games>python -m freegames.snake
```

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

## Adding changes to files that have changed
git add -u

## Restoring a file
git restore --staged README.md

## Git diff
git diff

### Showing changes to staged files
git diff --staged

## Commit a file
git commit -m "My commit message"

## Getting Updates
git fetch
git checkout master
git pull

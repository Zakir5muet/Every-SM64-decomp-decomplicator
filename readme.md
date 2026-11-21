# Every SM64 decomp decomplicator or ESM64DD for short.
ESM64DD sets up development environments for Nintendo 64 decompilation projects on Windows. Simply choose a
project template, select a project folder, and locate the base ROM, then let Decomplicator do the rest.

The original decomplicator: [download the latest version on the original one](https://github.com/LucretiaArc/Decomplicator/releases).

# Why?
Under normal circumstances, software developers can set up their own development environment. However, SM64
decompilation projects offer benefits even to the casual romhacker who is not interested in writing code. This also offers easy GUI compiling instead of running commands and downloading/installing alot of things. Traditionally,
setting up a development environment has presented a challenge for these users, with inscrutable errors creating
barriers to entry. ESM64DD seeks to remove these barriers, making decompilation projects accessible to the casual
romhacker.

# Caution: Project Templates
ESM64DD's project templates are used to download and run external software. A malicious project template could be
harmful to your computer, and put your personal data at risk. Only use a third-party project template if you fully trust
the author.

# Building/compiling
Use `uv` to set up the project environment, then run `build.py` in the project environment:
```
uv sync
uv run build.py
```
Please install uv then follow the build instructions in the readme. I wrote this targeting Python 3.14, so I haven't checked whether 3.10 will work, but uv will download a more recent version for you anyway, along with the other python dependencies you need.
# What's different from Decomplicator?
I'm making this project because decomplicator has 2 sm64/n64 decomps, so i wanted to expand it to have (for now) every or most SM64 decomps.

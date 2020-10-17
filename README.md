# file-move-planner

Plan out the reorganization of your file systems.

**This project is simply an idea placeholder. I have no plans to actually make
it.**


## The Premise

Sometimes you want to reorganize your file system. Perhaps you have a bunch of
pictures currently sorted into folders by the date and vacation, but now you
want to move everything so that they're organized by who's in them. Or maybe
you're like me and put everything in a "to sort" folder and have finally
decided, +10 years later, that dang it I'm actually going to sort things.

Well an issue comes up where moving files can take a long time - perhaps there
are thousands of them or perhaps they're really big. Moving them once and then
deciding later on that you want to put them somewhere else is annoying.

This project aims to fix that last point. With this project, you can map file
and folder paths from their existing location to a new one, all without
actually moving any files. This lets you orgnaize things quickly without having
to wait for transfers to finish.

Then, when you've finally decided where everything goes, you can hit **GO**
button and walk away. This tool will copy, move, and rename all the files
you've chosen.


## Features

+ [ ] Save and load migrations so that you can easily pick up where you left
    off. Files are saved as... JSON maybe? I haven't decided.
+ [ ] GUI written using either Tkinter (because it's bundled with Python) or
    flask (because I'm familiar with flask)
+ [ ] Estimate space used on target drive
+ [ ] Use proven tools to actually perform the move/copy action - `robocopy`
    and `rsync`.
+ [ ] Supports Windows and Linux (and I guess Mac, but I can't test that. But
    also Mac is basically linux so...)
+ [ ] View the final file structure prior to moving anything.
+ [ ] Restart a job after being interrupted.


## Installation and Usage


## Development

1.  Clone the repo: `git clone https://github.com/dougthor42/file-move-planner`
2.  Move into that dir: `cd file-move-planner`
3.  Create a virtual environment: `python -m venv .venv`
4.  Activate it: `. .venv/bin/activate`
5.  Install python packages:
    1.  `pip install -U pip setuptools wheel`
    2.  `pip install -r requirements.txt -r requirements-dev.txt`
    3.  `pip install -e .`
6.  Run tests to verify: `pytest`
7.  Ready to develop


## Changelog

See [CHANGELOG.md](.\CHANGELOG.md).

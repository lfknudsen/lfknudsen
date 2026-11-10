Welcome to my Git profile.

A list of some of my public projects follows. I have tried to categorise them a bit.

Most of my experience is with Java, C#, C, Go, Python, and SQL, but there
are also projects in other languages like C++, Rust, F#, and TypeScript.

I'm not particularly excited about LLMs, so you can be sure that any questionable code below is my own ;)

### Desktop applications

[Regless](https://github.com/lfknudsen/Regless):
Tool for developing regular expressions built in Java with JavaFX.

### Server-related programmes (Go, Flutter/Dart)

[Gown](https://github.com/lfknudsen/gown):
Universal download server. Also works as a standalone local command-line programme.

[Plume](https://github.com/lfknudsen/plume):
File upload server.

[Mark](https://github.com/lfknudsen/mark):
Bookmark database and management thereof.\
When used locally, can also import bookmarks from your browsers.

[Convoy](https://github.com/lfknudsen/convoy):
Message queue intended to work with Gown.

[Pact](https://github.com/lfknudsen/pact):
A private package manager.

[Tiara](https://github.com/lfknudsen/tiara):
Shared frontend for Gown, Mark, and Plume.

[Jade](https://github.com/lfknudsen/jade):
File management server akin to Dropbox, Mega, Google Drive, etc. - but with
a few unique features like tags.

### CLI Utilities (Go, C, F#, Python)

[Install](https://github.com/lfknudsen/install):
Install files on your PATH by moving them to the same location as this executable.

[Repo](https://github.com/lfknudsen/repo):
Conveniently create and update remote repositories with multiple hosts
from a single command-line interface.

[Push](https://github.com/lfknudsen/push):
Executes `git push` on each remote registered to the current Git repository.
Will retry once on failure.

[Gignore](https://github.com/lfknudsen/Gignore):
Easily generate a suitable `.gitignore` file.

[Guid/Uuid](https://github.com/lfknudsen/guid):
Generate a UUID automatically copied to your system clipboard.
Can also generate multiple at once.

[Colour](https://github.com/lfknudsen/colour):
Prints a table of ANSI colour codes.
If a number is given, it will display that particular colour code's output.

[Optimg](https://github.com/lfknudsen/optimg):
Optimises images using IrfanView and OptiPNG.

[Status](https://github.com/lfknudsen/status):
Reference HTTP status codes by searching for the code or name.

[Conv](https://github.com/lfknudsen/conv):
Currency, weight, and distance conversion in the command-line.

[Vauth](https://github.com/lfknudsen/vauth):
Command-line password manager.

[Gaze](https://github.com/lfknudsen/gaze):
Lists all the video files in the current directory, displaying their resolution, frame-rate, and bit-rate.

[Lsf](https://github.com/lfknudsen/lsf):
Lists all the files and sub-directories in the current directory, displaying
the size of each - even the sub-directories.

[Pykedex](https://github.com/lfknudsen/pykedex):
A command-line Pokédex.

#### Time-related utilities (Go)

[Timestamp](https://github.com/lfknudsen/timestamp):
Get the current UNIX timestamp automatically copied to your system clipboard.

[Timer](https://github.com/lfknudsen/timer):
Start a timer, displaying the time left. Plays a sound when finished.

[Stopwatch](https://github.com/lfknudsen/stopwatch):
Start a stopwatch.

[Clock](https://github.com/lfknudsen/clock):
Print the current date and time.

### Libraries

[Imari](https://github.com/lfknudsen/imari):
Extension methods for easier image editing in C#.

### Old programmes

[Scar](https://github.com/lfknudsen/scar):
A small interpreter I wrote as an experiment in seeing how I would go about
tackling such a project without looking up anything about compilers/interpreters.\
I believe I broke it at some point while trying to add conditional statements;
A good reminder to use dev branches. If nothing else, maybe someone will enjoy
looking at my terrible old C code :)

[mangaDB](https://github.com/lfknudsen/mangaDB):
A simple Flask website and database backend for managing a book/comic collection.

## Environment

I use PowerShell at the moment. You can find [my config file here](https://github.com/lfknudsen/pwsh-config).\
My library of [PowerShell cmdlets can be found here](https://github.com/lfknudsen/pwsh).\
Some of my favourites are:

[Change-Dir](https://github.com/lfknudsen/pwsh/blob/main/Change-Dir.ps1):
I override `cd` with this script, which turns `cd a b` into `cd "a b"`,\
and supports a backward and forward history with `cd -` and `cd +`.

[Goto](https://github.com/lfknudsen/pwsh/blob/main/goto.ps1):
If the input path is a file, it goes to the file's directory.\
If the input path is a directory, it goes to that directory.

[New-Dir](https://github.com/lfknudsen/pwsh/blob/main/New-Dir.ps1):
Creates a new directory and then enters it.
I alias this to `ndir`.

[Disk-Space](https://github.com/lfknudsen/pwsh/blob/main/Disk-Space.ps1):
List all of the drives along with their total and remaining space.
I alias this to `space`.

[Split-On](https://github.com/lfknudsen/pwsh/blob/main/Split-On.ps1):
Splits a string into an array, removing any empty elements.

[Cut-Prefix](https://github.com/lfknudsen/pwsh/blob/main/Cut-Prefix.ps1),
[Cut-Suffix](https://github.com/lfknudsen/pwsh/blob/main/Cut-Suffix.ps1):
For each input, removes the given prefix/suffix.

[Merge](https://github.com/lfknudsen/pwsh/blob/main/Merge.ps1):
Joins together the input strings, putting the first argument in-between each element.

## Other hosts

I have projects on [GitLab](https://gitlab.com/lfknudsen), [Codeberg](https://codeberg.org/lfknudsen),
and [GitHub](https://github.com/lfknudsen).\
As far as I recall, all my projects exist on GitHub, but new projects that I
make are hosted on all three, typically with GitLab representing the origin, and
the latter two being mirrors.
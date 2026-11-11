Thank you for visiting my Git profile.

I enjoy programming and have been doing it for many years now. I prefer working on the backend with
statically typed, compiled languages, but I care a lot about good user experience and interfaces,
too.\
Most of my experience is (in no particular order) with Java, C#, F#, C, Go, Python, PowerShell,
and SQL, but I have also done a few things in languages like C++, Rust, and TypeScript.

I have compiled a list of some of my public personal projects below, and I hope they can be helpful
 to your own development process or learning. Do not hesitate to make pull requests or open issues.

I'm not particularly interested in LLMs, so you can be sure that any questionable code is my own ;)

### Currently working on:
![Go icon](go_icon.png)[Gown](../../../../gown):
Universal download server. Also works as a standalone local command-line programme.\
Fully functional, but I want to tie it to a message queue with a variable number of worker nodes.

![Go icon](go_icon.png)[Convoy](../../../../convoy):
Message queue intended to work with Gown.

![Go icon](go_icon.png)[Mark](https://github.com/lfknudsen/mark):
Bookmark database and management thereof.\
When used as a standalone local application, can also import bookmarks from your browsers.

![Go icon](go_icon.png)[Pact](https://github.com/lfknudsen/pact):
A private package manager.

![Go icon](go_icon.png)[Jade](https://github.com/lfknudsen/jade):
Cloud drive akin to Dropbox, Mega, Google Drive, etc. - but better.

![Go icon](go_icon.png)[Vauth](https://github.com/lfknudsen/vauth):
Command-line password manager.

### Desktop applications

![Java icon](java_icon.png)[Regless](https://github.com/lfknudsen/Regless):
Tool for developing regular expressions built in Java with JavaFX.

![C# icon](cs_icon.png)[FindDuplicateDirs](https://github.com/lfknudsen/FindDuplicateDirs):
Tool to locate directories with the same name.

### Server-related programmes (Go, Flutter/Dart)

![Go icon](go_icon.png)[Plume](https://github.com/lfknudsen/plume):
File upload server.

![Dart icon](dart_icon.png)[Tiara](https://github.com/lfknudsen/tiara):
Shared frontend for Gown, Mark, and Plume.

#### Stubs

![Go icon](go_icon.png)[Distributed Exclusion](https://github.com/lfknudsen/DistEx):
A minimal implementation of the Ricart & Agrawala distributed exclusion algorithm.

![Go icon](go_icon.png)[Distributed Replication](https://github.com/lfknudsen/Replication):
A minimal implementation of an algorithm for distributed database replication.

### CLI Utilities (Go, C, F#, Python)

![Go icon](go_icon.png)[Install](https://github.com/lfknudsen/install):
Install files on your PATH by moving them to the same location as this executable.

![Go icon](go_icon.png)[Repo](https://github.com/lfknudsen/repo):
Conveniently create and update remote repositories with multiple hosts
from a single command-line interface.

![Go icon](go_icon.png)[Push](https://github.com/lfknudsen/push):
Executes `git push` on each remote registered to the current Git repository.
Will retry once on failure.

![F# icon](fs_icon.png)[Gignore](https://github.com/lfknudsen/Gignore):
Easily generate a suitable `.gitignore` file.

![Go icon](go_icon.png)[Guid/Uuid](https://github.com/lfknudsen/guid):
Generate a UUID that is automatically copied to your system clipboard.
Can also generate multiple at once.

![Go icon](go_icon.png)[Colour](https://github.com/lfknudsen/colour):
Prints a table of ANSI colour codes.
If a number is given, it will display that particular colour code's output.

![Go icon](go_icon.png)[Optimg](https://github.com/lfknudsen/optimg):
Optimises images using IrfanView and OptiPNG. Resamples exceedingly large files, converts .jpeg to
.png, and performs serious lossless compression.

![Go icon](go_icon.png)[Status](https://github.com/lfknudsen/status):
Reference HTTP status codes by searching for the code or name.

![C icon](c_icon.png)[Conv](https://github.com/lfknudsen/conv):
Currency, weight, volume, and distance conversion in the command-line.

![Go icon](go_icon.png)[Gaze](https://github.com/lfknudsen/gaze):
Lists all the video files in the current directory, displaying their resolution, frame-rate, and bit-rate.

![F# icon](fs_icon.png)[Lsf](https://github.com/lfknudsen/lsf):
Lists all the files and sub-directories in the current directory, displaying
the size of each - even the sub-directories.

![Go icon](go_icon.png)[NoTS](https://github.com/lfknudsen/nots):
**No** **T**railing **S**paces - Removes trailing whitespace from input file(s).

![Python icon](py_icon.png)[Pykedex](https://github.com/lfknudsen/pykedex):
A command-line Pokédex.

#### Time-related utilities (Go)

![Go icon](go_icon.png)[Timestamp](https://github.com/lfknudsen/timestamp):
Get the current Unix timestamp automatically copied to your system clipboard.

![Go icon](go_icon.png)[Timer](https://github.com/lfknudsen/timer):
Start a timer, displaying the time left. Plays a sound when finished.

![Go icon](go_icon.png)[Stopwatch](https://github.com/lfknudsen/stopwatch):
Start a stopwatch.

![Go icon](go_icon.png)[Clock](https://github.com/lfknudsen/clock):
Print the current date and time.

### Libraries

![C# icon](cs_icon.png)[Imari](https://github.com/lfknudsen/imari):
Extension methods for easier image editing in C#.

![F# icon](fs_icon.png)[Fiesta](https://github.com/lfknudsen/fiesta):
A tiny F# unit testing framework. Mostly made for fun; I tend to use XUnit or similar in practice.

![Go icon](go_icon.png)[LexGo](https://github.com/lfknudsen/LexGo)
A simple little lexer.

### Old programmes

![C icon](c_icon.png)[Scar](https://github.com/lfknudsen/scar):
A small interpreter I wrote as an experiment in seeing how I would go about
tackling such a project without looking up anything about compilers/interpreters.\
I believe I broke it at some point while trying to add conditional statements;
A good reminder to use dev branches. If nothing else, maybe someone will enjoy
looking at my terrible old C code :)

![Python icon](py_icon.png)[MangaDB](https://github.com/lfknudsen/mangaDB):
A simple Flask website frontend and database backend for managing a book/comic collection.

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

## Non-public projects

Some private university projects include:
- A Reddit-inspired social media phone app (React Native + TypeScript) with a Python FastAPI API-layer and PostgreSQL database
that supported registration and login via WhatsApp and e-mail. Also my first opportunity to try Scrum.
- A minimal GDPR-compliant Twitter clone in C# and Asp.Net Core deployed to Azure.
- A map and route-finding application written in Java with JavaFX.
- User-driven design and development as we worked with real users of an existing application.

## Other hosts

I have projects on [GitLab](https://gitlab.com/lfknudsen), [Codeberg](https://codeberg.org/lfknudsen),
and [GitHub](https://github.com/lfknudsen).\
As far as I recall, all my projects exist on GitHub, but new projects that I
make are hosted on all three, typically with GitLab representing the origin, and
the latter two being mirrors.

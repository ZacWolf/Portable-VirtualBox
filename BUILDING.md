To build Portable-VirtualBox from source do the following:

### Prerequisites

Obtain and install the following free tools

* AutoIt https://www.autoitscript.com/site/autoit/downloads/ (ver 3.3.14.3+)
* 7zip from http://www.7-zip.org/ (ver 19.00+)
* Resource Hacker from http://www.angusj.com/resourcehacker/ (ver 5.1.7+)

## Obtaining the source code

Check out the source code from GitHub. For example by using [GitHub on Windows](http://windows.github.com/) or use `git` from the command line like this:

`git clone https://github.com/ZacWolf/Portable-VirtualBox.git`

or via GitHubCLI: `gh repo clone ZacWolf/Portable-VirtualBox`

This will create a new folder named `Portable-VirtualBox`.

## Making a new version with the build script

Edit lines 12-14 of `build.bat` to provide the folder location of the three tools above:
Run the `build.bat` script. 
The new version should appear in the `build\release` directory.


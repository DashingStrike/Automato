# Automato
Automato is a LUA-based automation program which is useful for any automation task which primarily involves screen scraping and sending mouse clicks, with a special focus on automating video games.  Automato was originally called <i>Jimbly's VeggieTales</i>, as it was initially developed for growing vegetables in <i><a href="http://atitd.com">A Tale in the Desert</a></i>, but has grown to be used in other games as well.

Scripting reference and other documentation can be found on [the wiki](https://github.com/DashingStrike/Automato/wiki).

Get more general information on [the website](http://www.dashingstrike.com/Automato).

Join the [Automato Discord](https://discord.gg/XVUdwy8) to interact with other scripters.

For general Automato issues, you can contact us [here](https://gitreports.com/issue/DashingStrike/Automato), or if you have a GitHub account, please use the [Issues page](https://github.com/DashingStrike/Automato/issues).  For game/script-specific issues, please use the links below.

### Game-specific script repositories
* [A Tale in the Desert](https://github.com/DashingStrike/Automato-ATITD10)
* [Final Fantasy XIV](https://github.com/DashingStrike/Automato-FFXIV)
* [Atom Zombie Smasher](https://github.com/DashingStrike/Automato-AtomZombieSmasher)
* [Diablo 3](https://github.com/DashingStrike/Automato-Diablo3)
* [Realm of the Mad God](https://github.com/DashingStrike/Automato-ROTMG)

### Other script repositories
* [Examples](https://github.com/DashingStrike/Automato-Examples)
* [common scripts usable in all repositories](https://github.com/DashingStrike/Automato-common)

# Source Code

Source code for Automato itself is not required to create, edit, and maintain macros. It is available via public SVN (recommended to use [TortoiseSVN](https://tortoisesvn.net/downloads.html)): **svn://www.dashingstrike.com/other/VeggieTales**. Commit access available to anyone who asks. It might move it to GitHub someday, but external dependencies and Git don't work as magically as SVN.  To check out with a command-line client:
```
svn checkout svn://www.dashingstrike.com/other/VeggieTales
```
Or, git itself contains a rudimentary SVN client, so you can get the code and externals via these commands, but it takes a *really* long time, and will not automatically pull externals for you in the future to get updates, so really isn't recommended, unless you're just looking for a (really inefficient) way to get a snapshot of the code:
```
git svn clone svn://www.dashingstrike.com/other/VeggieTales Automato
git svn clone svn://www.dashingstrike.com/src/GLOV Automato/GLOV
git svn clone svn://www.dashingstrike.com/src/Projects/User/Automato Automato/Projects/User/Automato
```

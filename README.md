# dotfiles
This is a repository with my configuration files, those that in Linux normally
are these files under the `$HOME` directory that are hidden and preceded by a
dot, AKA __dotfiles__

## Content

That's the *current content* of this repository, and these are the more remarkable
files.

### `/awesome`

Configuration of [Awesome](http://awesome.naquadah.org/)

+ `/awesome/awdt.py` python script that allows me to test changes in the Awesome
  configuration. Starts a X session nested into the current session and served
  by Xephyr, with an test configuration (Awesome) running inside it.

+ `/awesome/prep.org` is a Org-mode format file in which I store the
  repositories, authors and licenses of the external libraries that I use in
  this configuration.

+ `/awesome/check_execs.py` & `/awesome/logger.py` are symbolic links to two
  python files that can be founded in this repository,
  <https://github.com/joedicastro/python-recipes>

### `/compton`

Configuration of [Compton](https://github.com/chjj/compton)

### `/dunst`

Configuration of [dunst](https://github.com/knopwob/dunst)

### `/emacs`

Configuration of [Emacs](http://www.gnu.org/software/emacs/)

### `/fontconfig`

Configuration of [fontconfig](http://www.freedesktop.org/wiki/Software/fontconfig)

### `/fonts`

The fonts that I use in my terminal, vim, etc ...

 - [Dejavu Sans Mono](http://dejavu-fonts.org) is a free public domain font and
   has the probably best Unicode support from all the monospaced fonts
   available.
 - Dejavu Sans Mono for Powerline is the same font adapted to use it with
   Powerline in Vim

### `/git`

Configuration of [git](http://git-scm.com/)

### `/gnupg`

Configuration of [GnuPG](https://www.gnupg.org/)

### `/gtk`

Configuration of the __Gtk__ theme to fix an error with the Gvim window

### `/hg`

Configuration of [Mercurial](http://mercurial.selenic.com/)

+ `/hg/bb_gh.py` a Python Mercurial hook to do `hg push` simultaneously to the
  same repository in both GitHub and Bitbucket sites

### `/livestreamer`

Configuration of [Livestreamer](https://github.com/chrippa/livestreamer)

### `/mpd`

Configuration of [mpd](http://mpd.wikia.com/wiki/Music_Player_Daemon_Wiki)

### `/ncmpcpp`

Configuration of [ncmpcpp](http://ncmpcpp.rybczak.net/)

### `/pentadactyl`

Configuration of [Pentadactyl](http://5digits.org/pentadactyl/)

### `/pylint`

Configuration of [Pylint](http://www.pylint.org/)

### `/ranger`

Configuration of [ranger](http://ranger.nongnu.org/)

### `/tmux`

Configuration of [tmux](http://tmux.sourceforge.net/)

### `/urxvt`

Configuration of [rxvt-unicode](http://software.schmorp.de/pkg/rxvt-unicode.html)

#### `/vim`

Configuration of [Vim](http://www.vim.org)

+ `/vim/vimrc` the Vim configuration file
+ `/vim/README.md` is a summary of my Vim configuration customizations
+ `/vim/spell/` files needed for spelling
+ `/vim/UltiSnips/` my custom [UltiSnips][ulsns] snippets

  [ulsns]: https://github.com/SirVer/ultisnips

### `/xsession`

Configuration of the __X__ session

+ `/xsession/xinitrc` bash script to setup the X session

### `/zathura`

Configuration of [zathura](http://pwmt.org/projects/zathura/)

NOTE: This fork is solely for https://aur.archlinux.org/packages/manly-git/.
Please see https://github.com/carlbordum/manly for the original project.

# manly
manly is a compliment to man pages.

It's a lot like [explainshell](https://explainshell.com)
(don't worry, that is explain-shell, not explains-hell).

Your good friend has a funky alias in [his dotfiles](
https://github.com/8Banana/dotfiles/blob/master/__Myst__/.zshrc):
`alias alert="notify-send -i terminal -t 5 'Alert from Terminal!'"`:

```
$ manly notify-send -it

notify-send - a program to send desktop notifications
=====================================================

      -t, --expire-time=TIME
              The duration, in milliseconds, for the notification to  appear  on  screen.
              (Ubuntu's Notify OSD and GNOME Shell both ignore this parameter.)

      -i, --icon=ICON[,ICON...]
              Specifies an icon filename or stock icon to display.

```

Short and sweet!


## Installation on Arch Linux
manly supports Python 2 and 3

    $ git clone https://aur.archlinux.org/manly-git.git
    $ cd manly-git
    $ makepkg -si

# NOPESHELL
_Your friendly shell to thrwart invaders._

This simple shell will prematurely end SSH connections.

### Instructions
1. Add this to `/usr/bin/nopeshell` or simlar path as root.
2. `chmod a+x` this file.
3. Add this file to `/etc/shells` so it is official!
4. Set users to login with this shell.
5. Profit! Or maybe just don't get hacked..?

### Bash One-Liner
    sudo curl -L "https://raw.githubusercontent.com/subfission/nopeshell/master/nopeshell" > /usr/bin/nopeshell && sudo chmod a+x /usr/bin/nopeshell && echo '/usr/bin/nopeshell' >> /ets/shells && echo "done."

### Supported Platforms
- MacOS 10.8+
- Linux

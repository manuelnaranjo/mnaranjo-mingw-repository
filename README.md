# mnaranjo msys2/mingw repository

# Usage

    $ wget https://raw.githubusercontent.com/manuelnaranjo/mnaranjo-mingw-repository/master/mirrorlist.mnaranjo-mingw32 -O /etc/pacman.d/mirrorlist.mnaranjo-mingw32
    $ vim /etc/pacman.conf
    # add the following section
    # [mnaranjo-mingw32]
    # Include = /etc/pacman.d/mirrorlist.mnaranjo-mingw32

    $ pacman -Syy

Now you can install packages from my repo

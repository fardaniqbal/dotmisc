Repo for miscellaneous config files.  For most of these files, make
symlinks in your home directory to the corresponding files here.  For
`htoprc`, symlink `~/.config/htop/htoprc` to the `htoprc` in this repo.

**!!! Important note for `.curlrc` !!!**  
The `.curlrc` file enables the `--insecure` flag!  You generally _do not_
want a symlink to this file in your home directory.  Only symlink to this
file as a workaround when you're on a company machine that uses a VPN,
proxy, Zscaler, etc that prevents curl from working correctly.

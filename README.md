# aliases
Set of command line aliases.
File must be named NAME_alias (for a single alias command) or NAME_alises (for multiple definitions).

Clone to your home directory and add the following to your .bash_rc file:
```
# Include person list of aliases.
if [ -d ~/aliases ]; then
  source <(cat ~/aliases/*_alias*)
fi
```

These should then load every time you log into the account(s) with a .bashrc containing the above lines.  To load manually (ex: after first cloning the repo and updating your .bashrc) type "source ~/.bashrc".

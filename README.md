## Installation

Put this in your `~/.bashrc` or `/etc/profile`:

```
backupdir=/tmp
rm(){   mv "$1" $backupdir; }
unrm(){ cp -r "$1" $backupdir/.; }
```

## Why

UX baby!

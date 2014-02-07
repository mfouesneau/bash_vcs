Versioning system control in your bash prompt
=============================================

This script add a tag to your prompt informing you when you enter a vcs
repository folder.

It works with git svn bzr and hg backends.

Installation
------------

Copy the `bash_vcs` into your home directory `~/.bash_vcs`
and add the following snippet to your `.bashrc`

```shell
# Include git svn bzr tree detection
if [ -f ~/.bash_vcs ]; then
    . ~/.bash_vcs
fi
```

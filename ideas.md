# Just a place for me to put my random thoughts

## C/C++ Sanitizers

It's practically criminal to teach a student who has never had to physically deal with memory before C/C++ without mentioning the `-fsanitize` flags in gcc/clang

## Git aliases

As someone who likes to overload basic commands to be more tuned for my personal use(See my .bashrc in [UsefulScripts](https://github.com/Pat-Lafon/UsefulScripts)), I'm rather annoyed that git does not support something like

```markdown
[alias]
    rm = 'branch -d'
```

in my .gitconfig file. Their reasoning over at the [git mailing list](http://git.661346.n2.nabble.com/allowing-aliases-to-override-builtins-to-support-default-options-td2438491.html) makes sense but I still find it to be unfortunate. For me at least, forcing new alias names or a wrapper around git is a clunky user experience.

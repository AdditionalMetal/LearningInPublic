# Global gitignore file

Set `excludesFile` in your `~/.gitconfig` to specify a global
gitignore file which is applied in addition to any project-specific
`.gitignore`

```
[core]
	excludesFile = ~/.gitignore
```

Or you can do this at the command line...

```bash
git config --global core.excludesFile ~/.gitignore
```

You can check if it is already configured with `--get` option...

```bash
git config --get core.excludesFiles
```

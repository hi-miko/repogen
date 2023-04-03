# Repository Generator (`repogen`)

This is a short script that lets you create a basic repository and instantly commit and push it to a remote server (whether its `github`
or something else).

```
Usage:
	repogen [FLAGS] [DIR]
Args:
	[DIR] -> optional argument that specifies where the repository should be created (defaults to the current directory).
Flags:
	'--name | -n <name>' -> The name of your remote repository
	'--url | -u <url>' -> The url of your remote repository
	'--license | -l [MIT | GPL3]' -> The license of your project
	'--help | -h' -> Displays this text and exits
	'--version' -> Displays the version of this script and exits
	'--ignore-license' -> tells the script to not add a license
```

Currently the `--ignore-license` flag is a workaround for the first problem in the `CHANGELOG.md`.

# kiss-style
a POSIX compliant KISS linux script to check if a package build file fits the style guidelines.

## Disclaimers

- This script doesn't check for bashisms or POSIX incompliance. You should not use this as a shellcheck replacement but rather as an addition to it.

- Although I tried to make this script detect as many inconsistencies as possible, it's not perfect and in some rare cases can report false errors (or even worse, not report anything at all) so it's best to still read and remember the [style guidelinesb(https://k1sslinux.org/wiki/kiss/style-guide).

## One line installation

```
echo "curl 'https://raw.githubusercontent.com/AndreiSva/kiss-style/main/kiss-style' >> /usr/bin/kiss-style && chmod +x /usr/bin/kiss-style" | sudo sh
```

Alternatively if you are using KISS linux and want to receive updates I will also be hosting a repository 

## Contributing

If you find any issues with this script feel free to create a pull request.

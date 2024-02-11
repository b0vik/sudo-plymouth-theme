## sudo-plymouth-theme
plymouth theme based off of the sudo mascot, as shown [here](https://wetdry.world/@max/111910989627736429)  

## installing
copy contents of repo to /usr/share/plymouth/themes/sudo, then run
```shell
doas plymouth-set-default-theme -R sudo
```

## kudos/helpful references
- brej's [plymouth theming guide](https://brej.org/blog/?p=158&cpage=1)
- the docs on plymouth's scripting language [here](https://www.freedesktop.org/wiki/Software/Plymouth/Scripts/)
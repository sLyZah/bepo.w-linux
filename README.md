# bepo.w-linux
A variant of the bépo layout, adapted for French, English and coding by Flamme. (http://bepo.fr/wiki/Utilisateur:Flamme/b%C3%A9po-intl)

## How to install?

You’ll have to modify 2 files.

### evdex.xml

Add this to `/usr/share/X11/xkb/rules/evdev.xml`
```
<variant>
  <configItem>
    <name>bepo_w</name>
    <description>French (Bepo, intl, Flamme Sly)</description>
  </configItem>
</variant>
```

### fr

Replace `/usr/share/X11/xkb/symbols/fr` with the `fr` file.
The additionnal layout starts at line 535 (https://github.com/sLyZah/bepo.w-linux/blob/31112aab31bdb45b33ccd9d8e567c0b9a1520fbf/fr#L535)

Relog :)

Thanks a lot to Flamme for this layout.

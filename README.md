# bepo.w-linux
A variant of the bépo layout, adapted for French, English and coding by Flamme. (http://bepo.fr/wiki/Utilisateur:Flamme/b%C3%A9po-intl)

## How to install?

You’ll have to modify 1 file.

### evdex.xml

Add this to `/usr/share/X11/xkb/rules/evdev.xml`
><variant>
>  <configItem>
>    <name>bepo_w</name>
>    <description>French (Bepo, intl, Flamme Sly)</description>
>  </configItem>
></variant>

### fr_bepo_intl

Add fr_bepo_intl to `/usr/share/X11/xkb/symbols/`

Relog :)

Thanks a lot to Flamme for this layout.

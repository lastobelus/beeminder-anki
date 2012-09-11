Anki 2.0 add-on that sends your review stats to [Beeminder](beeminder.com) and so keeps your graphs up-to-date.

It supports tracking all your reviews and just new cards. It's still somewhat experimental, but it shouldn't eat your dog. The only guarantee I can give is that I use it myself. :)

Installation:

Copy beeminder.py into your add-on folder or install through Anki (Tools -> Add-ons -> Browse & Install) with code [3491889895](https://beta.ankiweb.net/shared/info/3491889895).

Instructions:

1. Create goal at Beeminder.
2. Use type *Odometer*. This is required!
3. Set variables in add-on file (beeminder.py in your add-on folder).
4. Review!
5. Sync to AnkiWeb. This also sends the latest stats to Beeminder.

Known Issues / TODO:

1. Setting the options through some nice dialog window instead of manually editing the add-on file would be nice.
2. Only supports Odometer goals. It should also support Do More.
3. A few more sanity checks here and there would be nice too.
4. The number of reported new reviews in Beeminder's comments is sometimes wrong. This is purely cosmetic though.

Contact / Bugs:

muflax at (mail at muflax dot com) or on Github at <https://github.com/muflax/beeminder-anki>.

My own Beeminder graphs are at <https://www.beeminder.com/muflax/goals/anki> and <https://www.beeminder.com/muflax/goals/anki-new>.

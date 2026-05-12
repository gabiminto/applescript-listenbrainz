# applescript-listenbrainz
An Applescript service to post Apple Music tunes I like to Listenbrainz

## what it does

This action marks the current track as _loved_ and add it to your library. Then it sends its title/artist to Listenbrainz using their API.

## how to install

- Open the Automator app
- Create a Quick Action
- Set it to **No input**, **Any application**
- Add a workflow **Run applescript**
- Paste the code from the listenbrainz.applescript file there
- Change your library name     
    + in English, the library is called "Library"
    + in other languages, it gets a different name, for example in French it's called "Bibliothèque"
- Set your Listenbrainz user token directly in the code
- Save all as an Action (give it a meaningful name)

Now you should see the Action in the Services menu in any application menu.

## thanks

To encode json, this script uses https://github.com/mgax/applescript-json   
It might actually be easier to use Javascript now...

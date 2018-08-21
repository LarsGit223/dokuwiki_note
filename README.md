# DokuWiki Note plugin

A plugin for [DokuWiki](https://www.dokuwiki.org/) which allows users to easily insert four kinds of notes into the wiki pages.

## Usage

When you have it installed, use the following syntax `<note>message</note>`:

    <note>note</note>
![note](images/docs/note.png)

You can use the note keywords `important`, `warning` and `tip` to change the look of note as well

    <note important>important</note>
![note](images/docs/note_important.png)

    <note tip>tip</note>
![note](images/docs/note_tip.png)

    <note warning>warning</note>
![note](images/docs/note_warning.png)

## Notes

It is regularly reported that the cache needs to be cleaned after installing the plugin before the notes do showup. At least a full page-reload (CTRL-F5) is required.

## Limitations

Currently this plugin has some limitations:

 * Plugin won't work inside numbered lists
 * Plugin won't work inside tables

## Download / Installation

 See [DokuWiki's plugin page](https://www.dokuwiki.org/plugin:note)

Alternatively
 1. Download plugin/repo archive
 2. Installing the plugin:
    * You can either extract the archive into the <tt>lib/plugins</tt> directory or
    * Load the admin page and go to Manage Plugins and enter the URL of the plugin under Download and install the new plugin.-
 3. Update the `Configuration Settings` under the DokuWiki's admin page.

## Authors

 The plugin has been written from scratch by Olivier Cortéz. After the initial release it has been maintained
 by Olivier while he integrated several patches provided by the DokuWiki-community. Somewhere around the end
 of 2008 / start of 2009 Olivier started to became too busy with other (real-life) activities and occupations
 that active development and support halted. On 2009/06/15 Aurélien Bompard decided, after contacting
 Olivier Cortéz about it, to (temporarily) take-over maintenance and support for the plugin. On the
 same date Mischa The Evil opened a [GitHub-repository for the plugin](https://github.com/MischaTheEvil/dokuwiki_note)
 to make it a "real" community plugin. On the 16th a re-packaged release is available
 which "completed" the plugin (doc, license etc.).

## Credits

Many thanks to the following DokuWiki developers (in random order):

* Stephane Chamberland
* Carl-Christian Salvesen
* Eric Hameleers
* Christopher Smith
* Chris Lale
* Pixote
* Yves Bergeron
* Taylor Jones
* Luke
* Frédéric
* Kmosak
* foosel
* zerohalo

## License

This plugin is open-source and licensed under the GNU GPL v.2.

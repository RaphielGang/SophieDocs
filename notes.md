---
title: Notes
description: Save this Shiba pic please
published: 1
date: 2019-11-06T16:54:17.802Z
tags: 
---

Sometimes you need to save some data, like text or pictures. With notes, you can save any types of Telegram's data in your chats.
Also notes perfectly working in PM with Sophie.

## Available commands
- `/save (name) (data)`: Saves the note.
- `#(name)` or `/get (name)`: Get the note registered to that word.
- `/clear (name)`: deletes the note.
- `/notes` or `/saved`: Lists all notes.
- `/noteinfo (name)`: Shows detailed info about the note, who updated and created the note.
{.grid-list}

## Examples

An example of how to save a note would be via:
`/save data This is example note!`

Now, anyone using `/get data`, or `#data` will be replied to with `This is example note!`.

## Saving pictures and other non-text data

If you want to save an image, gif, or sticker, or any other data, do the following:
`/save word` while replying to a sticker or whatever data you'd like. Now, the note at `#word` contains a sticker which will be sent as a reply.

![Example saving picture](https://imgur.com/MEXBqMw.jpg =x400)

You can also add captions for pictures, just add caption text after `/save word` like:

![Example saving picture with caption](https://i.imgur.com/6fNmtql.png =x500)


## Saving notes from other Marie style bots
Sophie can save notes from other bots, just reply `/save` on the saved message from another bot, saving pictures and buttons supported aswell.

## Retrieving notes without the formatting
To retrieve a note without the formatting, use `/get (name) noformat`
This will retrieve the note and send it without formatting it; getting you the raw note, allowing you to make easy edits.

## Notes aliases
TODO in v2.0!

## Notes buttons and variables
Notes support inline buttons, read the [help page about buttons](other/buttons) to get started with using it.
Variables are special words which will be replaced by actual info like if you add `{id}` in your note it will be replaced by user ID which asked note, read the [help page about variables](notes/variables)

## Notes formatting and notes settings
Every note can contain special settings, for example you can change formatting method to HTML by `[format:html]` and fully disable it by `[format:off]`
### Notes settings list
- `[format:<md/html/off>]`: Change the note formatting
- `[preview]`: Enables the links preview in saved note
- `[encryption:<yes/no>]`: Note encryption (enabled by default)
{.grid-list}

![](https://i.imgur.com/oR7HI5X.png){.align-abstopright}
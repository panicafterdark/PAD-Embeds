# Panic Bot Commands

## Sending embeds

Create your series of embeds on [discohook](https://discohook.org/), then copy+paste the text in the "JSON data" field from the bottom in a text editor of your choosing and save it.

To send the embeds upload the file to discord with the comment `pad!send`. The message and file should be deleted and the the embeds should all be uploaded.

## Editing an Embed

As with sending embeds you need to create the file using the JSON data from discohook. But the command requires additional parameters to function: `pad!edit <Message ID> <embed num>`. Where `Message ID` is the ID of the embed your are trying to edit and `embed num` is the corresponding embed in the file starting at 0. If there is only one embed in the file you can leave this parameter off and just use `pad!edit <Message ID>`.

---
title: b!playlist
parent: Audio Commands
has_children: false
nav_order: 12
layout: default
---

# b!playlist information
Syntax: `b!playlist`

# Playlist configuration options.

- Scope info:
  - Global:
    - Visible to all users of this bot.
    - Only editable by bot owner.
  - Guild:
    - Visible to all users in this guild.
    - Editable by bot owner, guild owner, guild admins, guild mods, DJ role and playlist creator.
  - User:
    - Visible to all bot users, if --author is passed.
    - Editable by bot owner and creator.

# Subcommands:
`append` Add a track URL, playlist link, or quick search to a playlist.

`copy` Copy a playlist from one scope to another.

`create` Create an empty playlist.

`dedupe` Remove duplicate tracks from a saved playlist.

`delete` Delete a saved playlist.

`info` Retrieve information from a saved playlist.

`list` List saved playlists.

`queue` Save the queue to a playlist.

`remove` Remove a track from a playlist by url.

`rename` Rename an existing playlist.

`save` Save a playlist from a url.

`start` Load a playlist into the queue.

`update` Updates all tracks in a playlist.
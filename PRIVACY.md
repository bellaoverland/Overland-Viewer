# Overland Viewer – Privacy

Overland Viewer is a viewer for Second Life. **This software is not provided or supported by Linden Lab, the makers of Second Life.**

## What Overland keeps, and where

Everything stays **on your own computer**, in your Windows user folder (`%APPDATA%\Godot\app_userdata\Overland Viewer Prototype`):

- **Your login name** and, only if you tick "Remember me", **your password**. The password is encrypted with Windows' own protection for your Windows account (DPAPI), so it can be read only by you on this computer.
- **Your settings** (graphics, sound, favourites, the radio list).
- **Caches**: textures, shapes and objects already seen, so places load faster next time.
- **Logs**: what the viewer did, to find problems. They include the names of regions and people around you and the chat and messages you saw. `login_log.txt` is in your Documents folder (`Documents\OverlandViewer`), `godot.log` in the folder above.
- **The worn-things detector's lists** (`heads.txt`, `bodies.txt`, `problems.txt`, in `Documents\OverlandViewer`): makers, products and kinds of product seen around you - nothing about the people who wear them, who are only counted.

## What Overland sends, and to whom

- Your name and password go **only to Linden Lab's login server**, as with any Second Life viewer.
- While you are logged in, Overland talks **only to Second Life's servers** (Linden Lab), as every viewer does. When you log in it sends, as Linden Lab's viewer does, a one-way fingerprint (MD5) of your network card's address. The address itself is never sent.
- When it starts, Overland downloads two small public files from the project's GitHub page (the start-screen picture and the list of supporters) and asks GitHub, once a session, for the number of the newest version, to tell you when there is an update. Like any website visit, GitHub sees your computer's internet address; nothing about you or your account is sent.
- On the login page it reads Second Life's public status page (status.secondlifegrid.net), to say whether Second Life is working. Like any website visit, that page sees your computer's internet address; nothing about you or your account is sent.
- Overland sends **nothing to its developer** or to anyone else. There is no analytics and no tracking.
- The music of a parcel and the radio stations you choose are played from the addresses written by the parcel owner or by you.

## Logs you share

The logs never leave your computer by themselves. Help → "Send a report" only puts the log, your settings and your words into one file on your computer and opens the project's Issues page; you decide whether to attach it. If you send them to someone to get help, remember that they include chat, messages and names. Send them only to people you trust.

## Removing it

Uninstall Overland from Windows' "Apps" list. To also remove your settings, caches, logs and the saved password, delete the folders `%APPDATA%\Godot\app_userdata\Overland Viewer Prototype` and `Documents\OverlandViewer`.

## Contact

Questions: the project's page, https://github.com/bellaoverland/Overland-Viewer (Issues).

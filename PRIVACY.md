# Overland Viewer – Privacy

Overland Viewer is a viewer for Second Life. **This software is not provided or supported by Linden Lab, the makers of Second Life.**

## What Overland keeps, and where

Everything stays **on your own computer**, in your Windows user folder (`%APPDATA%\Godot\app_userdata\Overland Viewer Prototype`):

- **Your login name** and, only if you tick "Remember me", **your password**. The password is encrypted with Windows' own protection for your Windows account (DPAPI), so it can be read only by you on this computer.
- **Your settings** (graphics, sound, favourites, the radio list).
- **Caches**: textures, shapes and objects already seen, so places load faster next time.
- **Logs** (`login_log.txt`, `godot.log`): what the viewer did, to find problems. They include the names of regions and people around you and the chat and messages you saw.

## What Overland sends, and to whom

- Your name and password go **only to Linden Lab's login server**, as with any Second Life viewer.
- While you are logged in, Overland talks **only to Second Life's servers** (Linden Lab), as every viewer does. When you log in it sends, as Linden Lab's viewer does, a one-way fingerprint (MD5) of your network card's address. The address itself is never sent.
- When it starts, Overland downloads two small public files from the project's GitHub page: the start-screen picture and the list of supporters. Like any website visit, GitHub sees your computer's internet address; nothing about you or your account is sent.
- Overland sends **nothing to its developer** or to anyone else. There is no analytics and no tracking.
- The music of a parcel and the radio stations you choose are played from the addresses written by the parcel owner or by you.

## Logs you share

The logs never leave your computer by themselves. If you send them to someone to get help, remember that they include chat, messages and names. Send them only to people you trust.

## Removing it

Uninstall Overland from Windows' "Apps" list. To also remove your settings, caches, logs and the saved password, delete the folder `%APPDATA%\Godot\app_userdata\Overland Viewer Prototype`.

## Contact

Questions: the project's page, https://github.com/bellaoverland/Overland-Viewer (Issues).

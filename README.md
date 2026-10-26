# Overland Viewer

A viewer for Second Life, built on the Godot engine (Direct3D 12 or Vulkan), made to stay smooth and steady in crowded places.

> **This software is not provided or supported by Linden Lab, the makers of Second Life.**

## Download
The newest version is always here: **[Releases → Latest](https://github.com/bellaoverland/Overland-Viewer/releases/latest)** (`OverlandViewer-…-Setup.exe`, Windows).

## Support
Questions and problems: **[Issues](https://github.com/bellaoverland/Overland-Viewer/issues)**. Overland is made by one person in their free time; there is no paid support. To report a problem, attach `login_log.txt` (see Privacy below for what it contains).

## How it differs from Linden Lab's viewer
- Built on Godot, not on Linden Lab's viewer code.
- A "dispatcher" lightens the picture by itself when the computer is in trouble (crowds, a full graphics card) and brings it back when things calm down.
- Far avatars may be drawn as soft smoke until they are loaded, or when many people are around.
- **Not there yet**: voice chat, mesh upload, some build tools, particles, the older bump / shine maps, media on objects.

## Content
Overland shows Second Life as it is; it adds no content of its own beyond General maturity. What you see depends on the regions you visit and your own Second Life maturity settings.

## Privacy
Everything Overland keeps stays on your computer; your password goes only to Linden Lab. Details: **[PRIVACY.md](PRIVACY.md)**.

## Terms
Using Second Life means accepting Linden Lab's [Terms of Service](https://lindenlab.com/legal/second-life-terms-and-conditions). When they change, Overland shows them at login and asks for your agreement, as Linden Lab's viewer does.

## Uninstall
Windows Settings → Apps → Overland Viewer → Uninstall. Your settings, caches and logs are in `%APPDATA%\Godot\app_userdata\Overland Viewer Prototype`; delete that folder to remove them too.

## Built with
[Godot Engine](https://godotengine.org) (MIT licence) · [LibreMetaverse](https://github.com/cinderblocks/libremetaverse) (BSD licence) · CoreJ2K (BSD licence).


# Overland Viewer

A new, light Second Life® viewer for Windows, made with the Godot engine — by **Bella Overland software**.

Overland Viewer is built to be simple for new residents and kind to modest computers: the menus you know from Firestorm, without the hundreds of buttons, and an engine that keeps crowded places moving.

**[⬇ Download the latest version](../../releases/latest)** — `OverlandViewer-0.1.0-beta-Setup.exe`

> Beta: this is the first public version. Please report what goes wrong (see *Reporting a problem* below).

## What it does

- **Log in** to Second Life (with 2FA), *Remember me* and automatic login.
- **Walk, run, fly, sit, stand**; Firestorm-style AO from your `#Firestorm/#AO` sets.
- **Avatars**: mesh bodies, clothes, Bakes on Mesh, shapes and animations. While someone loads, a column of **boiling plasma** stands in their place — orange for women, blue for men — and burns away as the person appears.
- **World**: objects, mesh, **PBR materials** (with their own repeats), textures, animated textures, glow, object lights, water with waves, particles (torch flames, smoke, sparkles).
- **Sky**: Classic, Clear day, Sunrise, Sunset, Night.
- **Chat**, private IMs and **group chats** in their own windows; profiles; people nearby; offers (items, friendship, teleport, groups).
- **My groups**: see your groups, which one is active, make another active or none.
- **Places** and the **Favorites bar** — drag a landmark onto it.
- **Clothes** (everything you can wear, by store) and **Outfits** (Wear / Add).
- **📷 Photo**: one click, saved in your Pictures folder.
- **L$ balance** in the top bar; Marketplace and Buy L$ from the Avatar menu.
- **Build**: cube / cylinder / sphere where you look, move and stretch, Take, Delete.
- **Help** button with a short guide; **Stats** (Ctrl+Shift+1) shows where the time goes.

## Requirements

- Windows 10 or 11, 64-bit
- A graphics card with Direct3D 12 or Vulkan
- 8 GB of memory (16 GB for crowded clubs)

## Installing

1. Download `OverlandViewer-0.1.0-beta-Setup.exe` from [Releases](../../releases/latest).
2. Run it. Windows may show *“Windows protected your PC”* because the installer is new and not yet signed: click **More info → Run anyway**.
3. Start **Overland Viewer** from the Start menu and log in with your Second Life name and password.

## Known limits (beta)

- Very crowded places (30+ people) are still slow on modest graphics cards; only the nearest avatars are drawn in full (Settings → Avatars).
- No voice, no neighbouring regions yet.
- Particles are shown for objects, not for things avatars wear.

## Reporting a problem

The viewer writes a log to `Documents\OverlandViewer\login_log.txt`. In Stats (Ctrl+Shift+1), **Write to log** adds a snapshot of the moment. Send the log, with a few words about what happened, to Bella Overland in Second Life or join the **Inventory Companion** group in-world.

## Privacy

Your password is only saved if you tick *Remember me*, and then encrypted by Windows for your user account on this computer. Overland Viewer talks to Second Life's own servers (login, the world, the map) and reads its start-screen picture and contributors list from Bella Overland's GitHub. Nothing about you is sent anywhere else.

---

Overland Viewer is an independent third-party viewer. It is not made, endorsed or supported by Linden Lab. Second Life® is a trademark of Linden Research, Inc.

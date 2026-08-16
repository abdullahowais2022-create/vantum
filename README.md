# Vantum

**A free Minecraft launcher and client.**

Sign in with Microsoft, run as many instances as you like, each with its own
version, mods and worlds. Install mods from Modrinth in one click, and play.

In game, **Right Shift** opens the Vantum menu: HUD read-outs you can drag
anywhere, smooth zoom, toggle sprint, fullbright and more, all rebindable from
the menu itself.

- **Instances that stay out of each other's way.** Separate mods and worlds, one
  shared download, so a second instance on the same version is instant.
- **Your settings follow you.** Keybinds and video options stay the same across
  every instance, including imported ones.
- **Bring your setup with you.** Drag in a folder from another launcher and your
  mods, worlds, servers and settings come across.
- **Updates itself.** New versions download in the background; you click Restart.

Vantum installs into its own folder and never touches your existing Minecraft.

---

## Download

**[⬇ Download the latest version](https://github.com/abdullahowais2022-create/vantum/releases/latest)**

Grab `Vantum-Setup-x.x.x.exe` from the Assets list.

---

## Windows will warn you the first time. This is expected.

When you run the installer, Windows shows a blue box:

> **Windows protected your PC**
> Microsoft Defender SmartScreen prevented an unrecognised app from starting.

**What to click:**

1. Click **More info** (the small link in the blue box, easy to miss)
2. Click **Run anyway** (the button that appears underneath)

That's it. You only do this once.

### Why it happens

Windows shows this for any program that hasn't been signed with a paid
code-signing certificate. Those run to hundreds of dollars a year and require a
registered company, which is a real cost for an independent team and one we
haven't taken on yet.

Vantum is free, and we'd rather spend what we have on the client itself for now.
We're working on perks to support development, and a signing certificate is near
the top of the list once that's in place.

**It is not a virus warning.** Windows isn't saying it found anything harmful.
It's saying "I don't recognise the publisher of this file." Plenty of legitimate
software gets the same message. The big launchers avoid it only because they're
companies who paid for a certificate.

### If you'd rather check for yourself

Fair enough, you should be careful with .exe files from the internet. You can:

- Upload the installer to [VirusTotal](https://www.virustotal.com) and see it
  scanned by 70+ antivirus engines
- Check that you downloaded it from **this GitHub releases page** and nowhere else

---

## What you need

- **Windows 10 or 11**
- **A Microsoft account that owns Minecraft: Java Edition.** Vantum launches the
  game you own. It can't give you a copy.
- **Java.** Vantum finds it automatically if you already have Minecraft installed.

---

## First run

1. Open Vantum and **sign in with Microsoft**. A Microsoft sign-in window opens,
   so you sign in to Microsoft directly and Vantum never sees your password.
2. Click **+ New instance**, pick a version and Fabric, and hit Create
3. Press **PLAY**

Vantum downloads Minecraft and Fabric itself, into its own folder
(`%APPDATA%\Vantum`). **It never touches your existing Minecraft install.** Your
current worlds, mods and settings are completely separate and safe.

### Bringing over an existing setup

Drag a folder from another launcher anywhere onto the Vantum window, or use
**Import**. Your mods, worlds, servers and settings come across.

> Mods that belong to another launcher (Feather's, Lunar's, Badlion's) are left
> out. They only run inside their own launcher and would crash the game here.

---

## Updates

Vantum updates itself. When there's a new version it downloads quietly in the
background and shows a **Restart** button. Nothing interrupts you, and you never
reinstall by hand.

---

## Supporting Vantum

Vantum is free and stays free. We're independent, so the things that cost money,
like code signing, hosting, and the time to keep it current with Minecraft, come
out of our own pocket.

We're putting together **perks** for people who want to support the project. The
client itself won't be paywalled. The aim is to cover the running costs and get
that signing certificate so nobody sees a Windows warning again.

In the meantime, the free things that genuinely help:

- **Tell people about it.** The only reason anyone finds Vantum.
- **Report bugs** in [Issues](https://github.com/abdullahowais2022-create/vantum/issues),
  with the version and what you were doing.
- **Star the repo.** It makes the project easier to find.

---

## Questions

**Do I need to own Minecraft?** Yes. Vantum launches the copy you own; it can't
provide one.

**Will this mess up my normal Minecraft?** No. Vantum keeps everything in its own
folder (`%APPDATA%\Vantum`). Your existing worlds, mods and settings are untouched.

**Can I use it on servers?** Vantum's own features are read-outs and local
settings, nothing that gives an unfair advantage. That said, some servers ban
modified clients on principle, so check the rules where you play. The Elytra swap
module is off by default for exactly this reason.

**Does it work with my mods?** Yes, anything for Fabric on your instance's
version. Browse Modrinth from inside the app, or drop `.jar` files straight onto
an instance.

---

*Not affiliated with Mojang or Microsoft.*

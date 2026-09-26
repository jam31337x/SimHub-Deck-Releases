# SimHub Deck

SimHub Deck is a SimHub plugin and Stream Deck layout for sim racing. It puts live car information and a few driving controls on a Stream Deck+, can light a supported MOZA wheel, and can show the song playing on another PC.

The download on this page is the public installer, **1.5.0**. Later test builds are not in that zip.

## Download

[Download SimHub Deck 1.5.0](https://github.com/jam31337x/SimHub-Deck-Releases/releases/download/1.5.0/SimHubDeck-Setup-1.5.0.zip)

Release page: [SimHub Deck 1.5.0](https://github.com/jam31337x/SimHub-Deck-Releases/releases/tag/1.5.0)

Unzip the whole folder, then run `SimHubDeck-Setup.exe`. Discord cannot attach this zip. The grey Source code links on the release are empty GitHub archives, not the plugin.

## What it does

### Stream Deck

Deck uses a Stream Deck+ : eight keys and four dials. Setup installs game profiles you tick. A profile can switch when that game's program starts. An empty dial means that game has no checked control for it. A missing speed or tyre number stays unavailable. Deck does not fill the gap with zero or with another game's data.

Each profile ends with pedal gauges, a feel page, and a rig page.

### Lights

In SimHub, open SimHub Deck, then Lights. You can set RPM colours, flag flashes on the wheel buttons, and your own patterns. Startup, idle, and engine-start lighting are separate from the live RPM bar. A keyboard test turns on one key at a time.

Wheel lights need a MOZA wheel that Deck already knows and AZOM installed separately. This installer does not include a filmed check of every LED.

### Dashboards

Setup can install dashboard files for SimHub Dash Studio, including a phone-sized cluster you open on this PC. That is not the same thing as the physical MOZA CM2 screen. The CM2 still uses its own dash upload. Deck does not switch those pages for you.

A phone on another computer was not part of the 1.5.0 check.

### Wheel feel

The feel page stores force-feedback presets and applies them through AZOM. The rig page shows the live base force, rotation, and torque that AZOM reports. The wheel's own firmware still calculates the force. Deck does not add a second force filter.

Rattler, under Tools, is a short vibration test. It runs only when the base is healthy and a game is not running. It does not start by itself.

### Music

Tools, then Music, can pair a second PC that has YouTube Music open in the browser. That PC sends the title, artist, and whether the song is playing. The sound stays on the music PC.

A desktop window and a browser page can show that information for a stream. Lyrics appear only when the player page actually provides them. Many songs have words and no line times, so the line stays empty. Deck does not invent timing by spreading the words across the song. If the player is on an advert, Deck shows the title that player reports.

### Settings, updates, and support

Support can check for an update, export settings, and restore a backup. The backup leaves pairing secrets on your PC. An optional install count gives this PC a pilot number. You can turn that off.

## Equipment

- A Windows PC with SimHub. Setup asks for 9.6 or newer and recommends 9.12.
- An Elgato Stream Deck+ for the deck pages.
- For MOZA wheel lights and force-feedback presets, install [AZOM 1.5.7](https://github.com/giantorth/AZOM/releases/tag/v1.5.7) yourself. Setup detects it and does not download or replace it.
- Keep MOZA Pit House closed while AZOM is using the base. They share the same port.

A direct-drive base can move hard. If the base is in a bad state, switch it off and on at the power supply. Do not expect Deck to reconnect it for you.

Deck does not support every wheel, pedal set, or game. Profiles you can install are not the same as a checked control or a live telemetry field in every title.

## Install

1. Close SimHub, Stream Deck, and Pit House.
2. Unzip the release. Keep `LICENSE.txt` next to the setup program.
3. Run `SimHubDeck-Setup.exe` and accept the administrator prompt.
4. Read the notices and tick accept.
5. Check this PC. If something is missing, follow the line on screen and check again.
6. Tick only the game profiles you want.
7. Review, then Install or Repair. Repair keeps your settings.
8. Start Stream Deck, then SimHub, and open **SimHub Deck** in the left menu.

The plugin works without a payment.

## Community

- [Discord](https://discord.com/invite/35WRyyFBnD) for news and help
- [YouTube, InGamingX](https://www.youtube.com/@InGamingX)
- [Buy Me a Coffee](https://www.buymeacoffee.com/ingamingx)

Built by MJ Systems / InGamingX. In SimHub the name is **SimHub Deck**.

## Not in this installer

These are development notes, not features of the 1.5.0 zip:

- Sending a hardware report from Add my hardware. That intake is not set up, and Send is not available.
- A guarantee of synced lyrics for every song, or word-by-word highlighting.
- Extra pedal firmware, including BrakeBox. A normal USB joystick can already appear as a joystick in SimHub. BrakeBox is not a Deck integration.

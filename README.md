# SimHub Deck

SimHub Deck is a SimHub plugin and Stream Deck layout for sim racing. It puts live car information and a few driving controls on a Stream Deck+, can light a supported MOZA wheel, and can show the song playing on another PC.

The download on this page is the public installer, **1.5.30**.

## Download

[Download SimHub Deck 1.5.30](https://github.com/jam31337x/SimHub-Deck-Releases/releases/download/1.5.30/SimHubDeck-Setup-1.5.30.zip)

Release page: [SimHub Deck 1.5.30](https://github.com/jam31337x/SimHub-Deck-Releases/releases/tag/1.5.30)

Unzip the whole folder, then run `SimHubDeck-Setup.exe`. Discord cannot attach this zip. The grey Source code links on the release are empty GitHub archives, not the plugin.

## What it does

### Stream Deck

Deck uses a Stream Deck+ : eight keys and four dials. Setup installs game profiles you tick. A profile can switch when that game's program starts. An empty dial means that game has no checked control for it. A missing speed or tyre number stays unavailable. Deck does not fill the gap with zero or with another game's data.

Each profile ends with pedal gauges, a feel page, and a rig page. The page knob updates the keys while it turns, and the page it stops on is the one that stays up. Pedal positions and the steering angle follow the latest SimHub snapshot. A dial's label and its value sit on separate lines.

### Lights

In SimHub, open SimHub Deck, then Lights. Startup has 15 shows, idle has 15 effects, and a car without documented lights can use one of 15 RPM looks. A documented car keeps that car's lights. The pillars climb before the shift point. Flag flashes stay on the wheel buttons. Dark frames stay dim on purpose. A keyboard test turns on one key at a time. Three presets appear on AZOM's LFE page. You pick one there. Deck does not turn them on for you.

Wheel lights need a MOZA wheel that Deck already knows and AZOM installed separately. This installer does not include a filmed check of every LED.

### Dashboards

Setup can install dashboard files for SimHub Dash Studio, including a phone-sized cluster you open on this PC. That is not the same thing as the physical MOZA CM2 screen. The CM2 still uses its own dash upload. Deck does not switch those pages for you.

A phone on another computer was not part of the 1.5.0 check.

### Wheel feel

The feel page stores force-feedback presets and applies them through AZOM. Base FFB and the torque limit stay the settings you choose, in percent. The deck does not turn that percent into measured newton-metres, and it does not report clipping it cannot see. The rig page shows the live base force, rotation, and torque that AZOM reports. The wheel's own firmware still calculates the force. Deck does not add a second force filter.

Rattler, under Tools, is a short vibration test. It runs only when the base is healthy and a game is not running. It does not start by itself. If the wheel turns past 15 degrees, the status says so and shows the angle it measured. Center the wheel before the next start.

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

## If something looks wrong

- The deck says OFFLINE: open the Stream Deck app, then SimHub Deck, Controls.
- A key says Needs setup: that game has no keyboard key for the action, or the key has not been learned. Deck does not invent one.
- The wheel lights stay dark: the base is off, Pit House has the port, or the installed AZOM build is newer than 1.5.7 and has not passed the safety check. Blank lights are the safe result.
- Force feedback numbers are percents you set. They are not measured newton-metres, and a missing clip reading is not zero.

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

- Local development may include an ETS2 Stream Deck **CONDITION** page with large engine/gearbox/cabin/chassis/wheels/trailer wear and cargo-damage percentages on the keys (not dials). That page is not in the public 1.5.30 installer.
- There is no MOZA firmware-update mode.
- This PC’s local AZOM is 1.6.3 with Deck’s compatibility patch. A later local AZOM file is accepted only when the same safety-method contracts still match. The public installer still expects you to install AZOM 1.5.7 yourself. Setup does not download or replace it.
- Local development keeps one generated Stream Deck profile per game. ETS2 suspension and camera chords on this PC use Shift+letter so they do not share Numpad keys with windows, debug or quick-select. That bind change is not in the public 1.5.30 installer.

These are not promises of the 1.5.30 zip:

- A hardware report can be saved on this PC. Sending it stays off until the intake service is configured. The detected Windows name stays separate from a model name you type.
- A guarantee of synced lyrics for every song, or word-by-word highlighting.
- Extra pedal firmware, including BrakeBox. A normal USB joystick can already appear as a joystick in SimHub. BrakeBox is not a Deck integration.

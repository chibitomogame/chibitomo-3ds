# Chibitomo for 3DS

A free, single-player Chibitomo for 3DS family systems, made as homebrew.
Wake up in Roothollow with a chibitomo of your own, and collect all 270+ chibitomo from the main game.
No account or internet is required to play on 3DS.

<p align="center">
  <img src="install-qr.svg" width="220" alt="QR code that installs the latest chibitomo.cia with FBI" />
</p>

## Install

You need a 3DS family system set up to run homebrew, with FBI installed.

**With FBI and the QR code** (the quickest way)

1. Open FBI and choose **Remote Install**, then **Scan QR Code**.
2. Point the camera at the code above.
3. Confirm the install. Chibitomo appears on the HOME Menu.

**From the SD card**

1. Download `chibitomo.cia` from the
   [latest release](https://github.com/chibitomogame/chibitomo-3ds/releases/latest).
2. Copy it to your SD card.
3. Open FBI, find the file and choose **Install CIA**.

**From the Homebrew Launcher**

Copy `chibitomo.3dsx` from the
[latest release](https://github.com/chibitomogame/chibitomo-3ds/releases/latest)
into `sdmc:/3ds/` and start it from the Homebrew Launcher.

## Sound

Like all homebrew with sound, Chibitomo needs the console's DSP firmware on
the SD card at `sdmc:/3ds/dspfirm.cdc`. If you've never made it, run the DSP1
homebrew once and it saves the file there. Without it the game plays in
silence, and the title screen tells you so.

## Saves and updates

Your game saves to `sdmc:/3ds/chibitomo/`, as you go and whenever you choose
Save. Your settings are kept apart from it, so starting a new game keeps them.

To update, install the newer `chibitomo.cia` over the old one. Your save
stays.

## Credits

Game, creatures and music by Sharematter Inc. Built with libctru, citro2d and
citro3d, Tremor and libogg, cJSON and the Nunito typeface. Their licenses are
in `LICENSES.txt`, which comes with each release, and in the game under
Credits on the title screen.

Chibitomo for 3DS is free to play and to share unmodified, and you can stream
it and post videos of it: see [LICENSE.md](LICENSE.md) for the terms. It is
not made, sponsored or endorsed by Nintendo.

Play Chibitomo online at [chibitomo.com](https://chibitomo.com).

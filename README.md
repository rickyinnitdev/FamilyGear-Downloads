# Family Gear downloads

A personal mouse and keyboard studio for you and your friends.

## Install

[Download the latest Windows installer](https://github.com/rickyinnitdev/FamilyGear-Downloads/releases/latest)

Run the Setup .exe and open Family Gear. Close other configurators, click Add device and select your supported USB device. No GitHub account is needed to download or update.

Version 0.2.2 is the first installer with online updates configured. If you have an older build, install this version once. Newer stable versions download inside the app and offer Restart to update. [See all releases](https://github.com/rickyinnitdev/FamilyGear-Downloads/releases).

## Source and notices

Read the [AGPL license](LICENSE) and [third-party notices and attribution](THIRD_PARTY_NOTICES.md). These also accompany the app and its corresponding source.

Each installer includes the matching Family-Gear-source.zip and license notices. About & source opens the installed resources folder. Release assets also provide a separate matching source ZIP with editable code and build instructions. Family Gear is licensed under AGPL-3.0-or-later and uses OpenMouse protocol code; full attribution is included in the package.

## Suggestions

Use Share an idea in the app to preview your message. You can copy it to your group chat without login, or submit it as a public GitHub Issue using your own GitHub account. No device data is attached automatically. [View suggestions](https://github.com/rickyinnitdev/FamilyGear-Downloads/issues).

## Device support

Known VXE R1 transports, experimental MCHOSE Ace 60 / Ace 60 Pro firmware 1.18, and selected ATTACK SHARK models. Support is model-specific; some controls require a verified device read. AULA SC620 has experimental USB/2.4 GHz profile-1 support; other AULA models and the X11 native bridge are not implemented. Preview mode uses sample values and does not write hardware. This personal Windows build is unsigned.

## Device reports (0.2.3)

Open Scan devices in the Windows sidebar, scan connected devices, select your mouse/keyboard entries, type the actual model name and requested features, then Preview report. Share on GitHub using your own login, or Copy report for your group chat without an account. The scan does not write device settings or send anything automatically. Reports include selected device names/classes and USB VID/PID; no serial numbers or computer/account identifiers.

[Review device reports](https://github.com/rickyinnitdev/FamilyGear-Downloads/issues?q=is%3Aissue+%22%5BDevice+report%5D%22)

Version 0.2.4 groups extra Windows interfaces into one entry per connected mouse/keyboard. Audio/radio HID entries and hubs are hidden. The scan identifies connected working USB gear, not which device is currently being pressed or moved.

## Version 0.2.7

Corrects the CompX VXE R1 polling register. The built app was tested on a connected 3554:F58E receiver: Apply confirmed 800 DPI and 500 Hz, then restored the original 1600 DPI and 1000 Hz. Failed Apply keeps your selection and shows an inline result with Cancel changes. Existing DPI stage edits preserve other stages; stage switching still uses the physical DPI button. Other models retain their existing compatibility limits.

Check delay & optimize previews supported mouse settings and offers restore. It reads Windows pointer settings without changing Windows. It does not promise zero delay or identify the cause of game latency.

SC620 Test report & agreement enables optional local recording of connection and Apply outcomes. Reports distinguish device readback from physical behavior. Friends review and copy them into your group chat, or open a public GitHub issue form. Nothing is uploaded automatically, and recording can be stopped/deleted.

Version 0.2.8 fixes CompX R1 click debounce. The built app confirmed 2 ms on the connected F58E receiver, then restored its original 4 ms. The complete sensor settings row is checked before and after writing to preserve unrelated settings.

## Version 0.2.9

Adds the supplied AULA SC620 image to device cards and mouse preview. ATTACK SHARK X11 can use the Windows app's **Add ATTACK SHARK X11** native connection over USB or its 2.4 GHz receiver. Wake the mouse before adding it and close other configurators.

Experimental X11 controls include current DPI stages/colors, polling, debounce, sensor flags, lift-off distance, lighting/sleep, basic/media button assignments and profiles. The mouse must identify itself and confirm settings reads and writes. No physical X11 was available for verification; test one setting at a time. Macro and stage-count editing are not enabled. Dock RGB uses its physical button. Corresponding source and third-party license notices are included in every release.

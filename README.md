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

## Version 0.2.10

Corrects X11 receiver interface pairing using Windows physical-device groups. After updating, reconnect the 2.4 GHz receiver and use Add ATTACK SHARK X11. If it still fails, open Add device → X11 connection details, review the local interface report and copy it to your group chat. The report excludes paths, serial numbers and computer identifiers. Physical X11 verification is still needed.

## Version 0.2.11

Initial experimental ATTACK SHARK X68HE support (3151:502D): Add device → ATTACK SHARK X68HE using wired USB. Reads and verifies RGB and polling changes. Recognized Hall effect firmware-slot values are read-only. Trigger editing, physical key mapping, calibration, analog travel and advanced bindings remain unavailable pending verification. Physical X68HE testing is still needed. Matching source and notices are included.


## Version 0.2.12

Corrects X68HE polling/profile command separation and requires settings readback. Adds RGB keyboard illustration, effect tiles, digital key feedback, Load current settings and Cancel changes. X11 connections accept event collections on another interface only when Windows confirms the same physical device group. Failed connections now open the reviewed local interface report automatically; copy it for diagnosis. Physical X11/X68HE confirmation is still needed; HE editing and analog depth remain unavailable.

## Version 0.2.13

Adds optional automatic device reports to the developer’s Google Forms inbox. Agree once, then supported device connections and failed X11 connections generate read-only smoke checks with automatic delivery retries. No Google or GitHub sign-in is needed for friends. Device reports lets you disable uploads or delete queued reports. Reports contain app version, USB IDs, interface metadata and read outcomes, excluding serials, paths, typed keys and raw packets. Physical buttons, lighting and latency remain marked not tested.

X68HE adds richer RGB illustrations and reactive digital key feedback. Hardware controls still require verified device readback; Hall effect editing remains unavailable pending protocol verification. Matching source and licenses are included in the installer and release assets.


## Version 0.2.14

X68HE now opens in the main keyboard workspace with selectable keys, RGB preview, current settings, Cancel and explicit Apply. Adds firmware-aware actuation, release, rapid-trigger and bottom-deadzone controls. Each physical key needs release/hold verification before editing; stale settings and unconfirmed readback are rejected. Disabled RT preserves unused sensitivity bytes. Advanced bindings and calibration remain unavailable. RGB preview is illustrative; key feedback is digital. Tested with mocked devices; physical X68 testing is still needed. X11 receiver connection is not fixed in this release.

## Version 0.2.15

Adds X11 receiver pairing using the verified Windows USB composite parent when collection ContainerIds are missing or differ. Rejects unrelated receivers, USB hubs and ambiguous matches. Failed opt-in reports now include pairing and settings-read stage outcomes without paths or serials. After updating, close other mouse drivers, unplug/replug the receiver, wake the mouse and choose Add ATTACK SHARK X11. Mocked tests pass; physical X11 confirmation is still needed.

## Version 0.2.16

Corrects X11 settings decoding for legacy paired high-DPI flags, adds bounded read-only retries and names the setting that fails. Physical X11 confirmation is still needed. X68HE trigger editing is easier: click a key, hold it when prompted, then adjust its loaded settings with sliders or number inputs and Apply. Cancel restores device values; drafts survive tab changes. Faster overview reporting and RGB/polling operations avoid redundant HE transfers, while HE writes retain complete stale checks and readback. No factory defaults, resets or invented measurements.

## Version 0.2.17

X68HE recognized hardware revisions load their factory switch maps for direct trigger editing: click keys, adjust loaded sliders and Apply, without holding to unlock. Adds Multicolor control; Constant and color selection turn it off. Corrected physical layout and multi-selection. X11 displays progress and the actual failure and uses batched, bounded Windows interface lookup. Physical receiver confirmation is still needed.

## Version 0.2.18

Fixes X11 connection timeout racing its Windows discovery helper. Queries only enumerated X11 HID instance metadata rather than all present PC devices. Connection UI shows progress and allows time for identity and current settings reads. Physical X11 confirmation remains outstanding.

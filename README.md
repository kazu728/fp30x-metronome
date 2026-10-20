# fp30x-metronome

A page for controlling the Roland FP-30X's built-in metronome over Bluetooth (BLE MIDI) from Chrome on an Android tablet. It uses SysEx to read and change the metronome's start/stop state, tempo, time signature, volume, and sound.

This is an unofficial tool, not affiliated with or endorsed by Roland Corporation. The addresses were obtained through reverse engineering. Sources and hardware verification notes are recorded as comments next to the address table in `index.html`. All code, styles, and address data are included in that file, so only `index.html` is needed for hosting.

## Manual verification

Connect to an FP-30X and check that starting and stopping the metronome and changing the tempo, time signature, volume, and sound take effect on the piano. Also check that settings are read again after reconnecting and after returning to the page.

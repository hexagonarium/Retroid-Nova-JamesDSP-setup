# Preset details

- **Speakers:** +3.8 dB output, −0.1 dB limiter / 500 ms release; bundled stereo-widener script at width 2. The stored conventional EQ is disabled.
- **KZ Castor Bass 0011:** AutoEQ GraphicEQ, normalized headroom already included; don’t add the parametric-EQ preamp again. Other EQ, bass boost, and widening are off. Output gain 0 dB; limiter −1 dB / 60 ms.
- **XR / flat headphones:** no EQ or widening; gain 0 dB; limiter −1 dB / 60 ms. XR has no invented device-specific correction.

The speaker preset embeds its Liveprog source. To replace an existing differently tuned `stereowide.eel`, import the supplied source through JamesDSP’s Liveprog library or use the embedded script on a fresh installation; the app may retain parameters from an existing local script.

## Credits

Castor correction: [AutoEQ / ToneDeafMonk, exact off-off-on-on measurement](https://github.com/jaakkopasanen/AutoEq/tree/master/results/ToneDeafMonk/in-ear/KZ%20Castor%20Improved%20Bass%20Version%20%28off-off-on-on%29). See `LICENSES/AutoEq-MIT.txt`.

Speaker widener: [JamesDSP bundled EEL source](https://github.com/timschneeb/RootlessJamesDSP/blob/master/app/src/main/assets/Liveprog/stereowide.eel), based on the linked MusicDSP stereo-width algorithm. Included source: `source/stereowide.eel`; license: `LICENSES/JamesDSP-GPL-3.0.txt`.

These are portable sound presets, not a whole-device backup. No account data, crash logs, APKs, or firmware audio configuration is included. Rootless builds and older JamesDSP preset formats were not tested.

# Retroid Nova JamesDSP setup

Three importable audio presets for **JamesDSP 1.6.14 root edition**, tested on Retroid Pocket Nova / Android 13.

## Download

[Complete preset pack](retroid-nova-jamesdsp-setup-v1.0.0.zip?raw=true)

| Output | Preset | Settings |
|---|---|---|
| **Nova speakers — main/default** | [Nova-Speakers-3.8dB.tar](Nova-Speakers-3.8dB.tar?raw=true) | +3.8 dB gain; existing stereo widener |
| KZ Castor Bass, switches **down/down/up/up (0011)** | [Headphone AutoEQ](headphone-xr/KZ-Castor-Bass-0011-AutoEQ.tar?raw=true) | Matched ToneDeafMonk/AutoEQ correction; 0 dB extra gain |
| RayNeo Air 4 Pro / DP audio | [XR preset](headphone-xr/RayNeo-Air-4-Pro-XR.tar?raw=true) | Neutral; 0 dB gain |

Headphone/XR limiter ceiling: −1 dB. [Flat headphone alternative](headphone-xr/KZ-Castor-Clean.tar?raw=true).

## Import and switch automatically

Requires a **working root JamesDSP driver** and the matching app. [Official root setup](https://github.com/timschneeb/RootlessJamesDSP/blob/master/BUILD_ROOT.md). Presets do not install a driver.

1. Download/extract the pack on the Nova. Keep the individual **`.tar` presets intact**.
2. JamesDSP → **Presets → Add → Import**; select a `.tar`.
3. With speakers active, load the main preset. Connect the KZ, then load its preset. Connect XR alone, then load the XR preset.
4. Keep **device profiles** enabled in JamesDSP settings. Switching outputs then recalls their settings automatically.

Use **Presets**, not full **Backup and restore**. If desired, save your current sound first: **Presets → Add → New preset**.

## Export your changes

While the desired output is active: **Presets → Add → New preset**. Long-press the saved preset → **Share…** to export its `.tar`. Load a preset while its intended output is active.

## Notes

The 3.5 mm profile applies to all wired headphones. Nova reports XR audio generically as HDMI/DP. Other firmware/devices are unverified. Lower speaker gain if you hear distortion; +3.8 dB is this Nova’s chosen setting.

[Preset details and credits](PRESETS.md) · [XR display/Tasker setup](https://github.com/hexagonarium/retroid-pocket-nova-auto-xr-setup)

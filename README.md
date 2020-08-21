# sds

## Requirements
- Python 3.8.5
- pulseaudio 13.0
- GTK 3.24.22
- PyGObject 3.36.1

## Configuration
sds looks for a configuration file at `~/.sds.json`. Example:

```
{
  "hidden": ["alsa_output.pci-0000_00_1b.0.iec958-stereo"],
  "display_names": {
    "alsa_output.usb-Creative_Technology_Ltd_Sound_Blaster_Play__2-00.analog-stereo": "Headphones",
    "alsa_output.usb-041e_30d3_140106000C2B-00.analog-stereo": "Speakers"
  }
}
```

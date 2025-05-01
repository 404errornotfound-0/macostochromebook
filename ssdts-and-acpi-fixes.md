croscorebootpatch: Fixes freeze during boot when using coreboot 4.20 and newer. Not needed when custom rom is used.

Keyboard Map: Maps FNx keys to ChromeOS mapping. This is an example, you may need to do your own mapping.
Will need to be compiled with either iASL or MaciASL.

Fake Ambient Light Sensor: Creates a fake ambient light sensor which is needed by macOS to recognize the keyboard backlight.
This is only needed if your device does not come with a light sensor.

A pre-compiled version comes in OpenCore's release zip under Docs/AcpiSamples/Binaries/SSDT-ASL0.aml

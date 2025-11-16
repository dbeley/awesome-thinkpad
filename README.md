# Awesome ThinkPad

A curated list of community projects for Lenovo ThinkPad laptops inspired by [awesome](https://github.com/sindresorhus/awesome).

## Contents
- [Firmware and Boot](#firmware-and-boot)
- [Drivers and Kernel](#drivers-and-kernel)
- [Power Management and Thermal](#power-management-and-thermal)
- [Utilities](#utilities)
- [Hardware Mods](#hardware-mods)
- [Documentation and Community](#documentation-and-community)

## Firmware and Boot
- [coreboot](https://www.coreboot.org/) - Open source BIOS replacement for many models.
- [Libreboot](https://libreboot.org/) - Distribution of coreboot focused on freedom and privacy.
- [Heads](https://github.com/osresearch/heads) - Tamper-evident firmware with coreboot and Linux.
- [Dasharo](https://dasharo.com/) - Modern open firmware available on select ThinkPads.
- [Skulls](https://github.com/merge/skulls) - Pre-built coreboot images and flashing guides for xx30-era ThinkPads.
- [1vyrain](https://github.com/n4ru/1vyrain) - Script to unlock xx30 series BIOS for custom images.
- [IVprep](https://github.com/n4ru/IVprep) - Downgrades xx30-series BIOSes to 1vyrain-compatible builds to streamline coreboot installs.
- [thinkpad-firmware-patches](https://github.com/digmorepaka/thinkpad-firmware-patches) - Community-maintained collection of UEFI patches for ThinkPad firmware.

## Drivers and Kernel
- [thinkpad-acpi](https://github.com/torvalds/linux/tree/master/drivers/platform/x86) - Linux driver providing hotkeys and sensors.
- [tp-smapi](https://github.com/evgeni/tp_smapi) - Access ThinkPad embedded controller functions on older models.
- [thinkfan](https://github.com/vmatare/thinkfan) - Simple fan control program.
- [throttled](https://github.com/erpalma/throttled) - Fix Intel CPU throttling on newer laptops.

## Power Management and Thermal
- [TLP](https://github.com/linrunner/TLP) - Advanced power management tools for Linux.
- [auto-cpufreq](https://github.com/AdnanHodzic/auto-cpufreq) - Automatic CPU speed & power optimizer.
- [tpacpi-bat](https://github.com/teleshoes/tpacpi-bat) - Set per-battery charge thresholds via ACPI calls without vendor software.
- [FakeSlice](https://github.com/n4ru/FakeSlice) - Windows tool that forces USB-C power banks to discharge first, emulating removable slice batteries.
- [zcfan](https://github.com/cdown/zcfan) - Zero-configuration Linux daemon that keeps fans off when safe without inducing throttling.

## Utilities
- [TPFanCtrl2](https://github.com/Shuzhengz/TPFanCtrl2) - Windows fan speed utility.
- [acpi-call](https://github.com/mkottman/acpi_call) - Kernel module to call ACPI methods (e.g. disable discrete GPU).
- [ThinkPadLEDControl](https://github.com/valinet/ThinkPadLEDControl) - Control chassis LEDs and bind them to system events on Windows.
- [GhostBusterPlus](https://github.com/joncox123/GhostBusterPlus) - Customize the e-ink cover on ThinkPad Plus Gen 4 systems.
- [keyboard-backlightd](https://github.com/VorpalBlade/keyboard-backlightd) - Linux daemon that turns off the keyboard backlight after inactivity.
- [NubRub](https://github.com/RubenKremer/NubRub) - Windows tray app that plays custom audio when the TrackPoint moves.
- [dockd](https://github.com/libthinkpad/dockd) - Lightweight daemon that switches display and I/O profiles automatically when docking and undocking on Linux.
- [ThinkpadAssistant](https://github.com/MSzturc/ThinkpadAssistant) - macOS companion that restores Fn shortcuts, wireless toggles, and keyboard backlight control on Hackintosh builds.
- [thinkmorse-rust](https://github.com/theritvars/thinkmorse-rust) - Rust rewrite of the lid LED Morse flasher for playful EC-driven notifications.

## Hardware Mods
- [thinkpad-ec](https://github.com/hamishcoleman/thinkpad-ec) - Unofficial BIOS/EC patches.
- [NitroPad](https://www.nitrokey.com/nitropad) - Pre-flashed coreboot/Heads ThinkPads.
- [ThinkpadBattery](https://github.com/iam4722202468/ThinkpadBattery) - Open hardware replacement battery for the T420 series.
- [tp-compact-keyboard](https://github.com/lentinj/tp-compact-keyboard) - Adds Fn-Lock switching to the TrackPoint Compact Bluetooth Keyboard.
- [arduino-thinkpadkb-usb](https://github.com/rampadc/arduino-thinkpadkb-usb) - Arduino Micro adapter that turns classic 7-row keyboards with TrackPoint into modern USB devices.
- [Lights Out](https://github.com/xairy/lights-out) - Demonstrates reflashing the X230 webcam to gain LED control; valuable reference for firmware-level hardware mods (use with caution).

### Mechanical & Ortholinear Keyboard Swaps
- [ThinKeys](https://github.com/moduloindustries/thinkeys) - Split ortholinear drop-in module with TrackPoint support and QMK firmware that directly replaces the stock keyboard on T410/T420/T430, T510/T520/T530, W510/W520/W530, and X220/X230 systems.
- [ThinkPad W530 OLKB](https://github.com/Michal-Szczepaniak/thinkpad-w530-olkb) - Preonic-style PCB that bolts into xx20/xx30 ThinkPads, uses a Raspberry Pi Pico controller, supports PG1425 low-profile switches, and exposes smart-card and Bluetooth headers for neat USB power/touchpad hookups.
- [Pineapple series](https://github.com/saoto28/pineapple60) - Ongoing set of Alice-style and split TrackPoint builds (see the [X13 Gen2 guide](https://note.com/saoto28/n/n716b7ca2e1f9)) documenting how to replace T470s/X13 keyboards with Kailh PG1316 mechanical switches while wiring the new PCB to the internal smart-card USB bus.
- [Clacktop mechanical Yoga mod](https://hackaday.com/2024/07/18/mechanical-keyboard-laptop-clacktop/) - Marcin Plaza's Lenovo Yoga 730 rebuild that replaces the chassis top with a titanium frame, squeezes in a slim mechanical keyboard, and retains full laptop functionality inside a custom acrylic-bottom shell.

## Documentation and Community
- [ThinkWiki](https://thinkwiki.org/) - Wiki with extensive Linux info.
- [ThinkPads Forum](https://forum.thinkpads.com/) - Long-running message board.
- [r/thinkpad](https://www.reddit.com/r/thinkpad/) - Active subreddit for discussion and support.
- [DankPads](https://dankpads.com/) - Wiki covering the used market prices of ThinkPads.
- [Coreboot-ThinkPads](https://github.com/bibanon/Coreboot-ThinkPads) - End-to-end guides for installing coreboot on many ThinkPad generations.
- [thinkpad-bios-software-flashing-guide](https://github.com/gch1p/thinkpad-bios-software-flashing-guide) - Tutorial for flashing coreboot without external programmers.
- [linux-thinkpad-speaker-improvements](https://github.com/shuhaowu/linux-thinkpad-speaker-improvements) - Community walkthrough for extracting Dolby impulse responses and recreating Lenovo’s audio tuning on Linux.

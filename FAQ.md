# Frequently Asked Questions (FAQ)

Common questions and answers about the GEEKRIA Mini Macro Keyboard.

## General Questions

### What is a macro keyboard?
A macro keyboard is a specialized input device with programmable keys that can execute complex commands, shortcuts, or sequences with a single key press. It's designed to increase productivity and efficiency.

### Do I need special drivers?
No! The keyboard works plug-and-play with default functions (arrow keys and volume control). You only need the configuration software if you want to customize the keys.

### Can I use this keyboard with my laptop?
Yes! As long as your laptop has a USB port, the keyboard will work. It's compatible with Windows and MacOS laptops.

### How many keys can I program?
You can program all 4 keys plus the rotary encoder (knob). The knob has two functions: rotation (volume up/down or custom) and press (mute/unmute or custom).

### Can I save multiple profiles?
Yes! The configuration software allows you to create and save multiple profiles for different applications or use cases.

---

## Compatibility Questions

### Is it compatible with Windows 11?
Yes! The keyboard is compatible with Windows XP, 7, 8, 10, and 11.

### Does it work with MacOS?
Yes! Full support for MacOS, including the configuration software. A separate MacOS installer is provided.

### Will it work with Linux?
Basic functionality (HID standard keys) should work, but the configuration software is not officially supported. Advanced users may be able to program it using alternative methods.

### Can I use it with my iPad or Android tablet?
Not officially supported. The keyboard requires the configuration software which runs on Windows or MacOS. Basic HID functions might work, but customization won't be available.

### Does it work with game consoles (PS5, Xbox)?
No, it's designed for PC and Mac only. Console support is not available.

---

## Software Questions

### Why does my antivirus flag the software?
This is a common false positive for low-level hardware control software. The software is safe - it only communicates with the keyboard hardware. You can:
- Add the folder to your antivirus exceptions
- Check the software on VirusTotal for verification
- The software has no network activity and only accesses the USB device

### Where can I download the software?
The software is included:
1. In this GitHub repository (Windows RAR and MacOS ZIP files)
2. On the USB flash drive that comes with the keyboard
3. Both sources contain the same software

### Do I need to install the software every time I use the keyboard?
No! Once you configure the keyboard, the settings are saved to the keyboard's memory. You only need to run the software when you want to change the configuration.

### Can I use the keyboard on multiple computers?
Yes! Your configuration is saved to the keyboard, so it works with the same settings on any computer you plug it into. No software installation needed on additional computers unless you want to reconfigure.

### How do I update the software?
Check this repository for the latest version. Download and extract the new version, then run it. Your saved profiles should remain intact.

---

## Configuration Questions

### What can I program the keys to do?
You can program:
- Single key presses (any keyboard key)
- Key combinations (Ctrl+C, Alt+Tab, etc.)
- Text strings (macros)
- Multimedia controls (play, pause, etc.)
- Mouse buttons
- Application-specific shortcuts
- Complex command sequences

### Can I make keys type entire sentences?
Yes! You can program keys to type text strings, making it perfect for frequently used phrases, email templates, or code snippets.

### How long can a macro be?
This depends on the software limitations. Generally, you can create macros with multiple key presses and reasonable delays between them.

### Can I add delays in macros?
Most macro functionality includes the ability to add delays between key presses, which is useful for complex command sequences.

### Can the knob control things other than volume?
Yes! You can program the knob to:
- Scroll up/down
- Zoom in/out
- Adjust brush size (in photo/video editing)
- Scrub timeline
- Any key press sequence for rotation
- Any command for the press function

---

## Hardware Questions

### What type of switches does it use?
Silent Red Axis mechanical switches, which provide a smooth, quiet typing experience without the loud clicking sound.

### How durable is the keyboard?
The keyboard uses quality mechanical switches rated for millions of keypresses. The acrylic construction is solid and durable for regular use.

### Is the knob smooth or does it have detents (clicks)?
This depends on the specific model, but most rotary encoders have smooth rotation with tactile feedback when pressed.

### Can I replace the switches?
The switches are not designed to be user-replaceable. This is a complete unit, not a DIY keyboard kit.

### How long is the cable?
The USB cable is 2 meters (200 cm / 6.5 feet) long, providing plenty of reach for most desk setups.

### Does the keyboard remember settings if unplugged?
Yes! Configuration is stored in the keyboard's onboard memory. It retains all settings even when unplugged.

### Can I turn off the LED lights?
Yes! You can customize or completely disable the LED backlighting using the configuration software.

---

## Troubleshooting Questions

### My keyboard isn't lighting up. What should I do?
Try:
1. Different USB port (use a direct port, not a hub)
2. Restart your computer
3. Try a different computer to isolate the issue
4. Check the cable for damage
See [TROUBLESHOOTING.md](TROUBLESHOOTING.md) for more details.

### The configuration software won't open. Help!
**Windows:** Right-click and "Run as administrator", and add to antivirus exceptions
**MacOS:** System Preferences → Security & Privacy → "Open Anyway"
See [TROUBLESHOOTING.md](TROUBLESHOOTING.md) for complete solutions.

### My keys stopped working after programming. What happened?
1. Verify settings in the configuration software
2. Reset to default settings
3. Disconnect and reconnect the keyboard
4. Restart the computer
See [TROUBLESHOOTING.md](TROUBLESHOOTING.md) for detailed steps.

### Can I reset the keyboard to factory defaults?
Yes! Use the configuration software's reset function, or consult the troubleshooting guide for reset procedures.

---

## Use Case Questions

### Is this good for gaming?
Yes! Gamers use it for:
- Quick access to abilities/items
- Push-to-talk
- In-game shortcuts
- Volume control while gaming
See [USE_CASES.md](USE_CASES.md) for specific gaming configurations.

### Can I use it for video editing?
Absolutely! It's popular with video editors for:
- Play/pause/cut shortcuts
- Timeline scrubbing with the knob
- Undo/redo quick access
- Render queue management
See [USE_CASES.md](USE_CASES.md) for video editing setups.

### Is it useful for programming/coding?
Yes! Developers use it for:
- Build/run/debug shortcuts
- Terminal commands
- IDE navigation
- Git commands
See [USE_CASES.md](USE_CASES.md) for development configurations.

### Can I use it for live streaming?
Perfect for streaming! Use it for:
- Start/stop recording
- Scene switching
- Audio control
- Mute microphone
See [USE_CASES.md](USE_CASES.md) for OBS/Streamlabs setups.

---

## Purchase Questions

### Where can I buy this keyboard?
The GEEKRIA Mini Macro Keyboard is available on:
- Amazon
- Other online retailers
- GEEKRIA's official channels

### What's included in the box?
- 1× Mini Macro Keyboard (4 keys + knob)
- 1× USB Cable (2 meters)
- 1× USB Flash Drive (with software)
- 4× Anti-slip rubber pads

### Is there a warranty?
Warranty terms depend on your place of purchase. Check with the retailer or GEEKRIA for warranty information.

### What if my keyboard is defective?
Contact the retailer where you purchased it for returns/exchanges, or reach out to GEEKRIA support for warranty service.

---

## Advanced Questions

### Can I use this with AutoHotkey?
Yes! You can use the keyboard with AutoHotkey scripts. Program the keys to trigger specific key combinations, then use AutoHotkey to expand those into more complex actions.

### Is there an API or SDK for custom software?
Not officially. The keyboard uses standard HID protocol, so advanced users might be able to interface with it programmatically, but this is not officially supported.

### Can I program different functions for short press vs long press?
This depends on the software capabilities. Check the configuration software for advanced features like press duration detection.

### Can I use QMK firmware with this?
This keyboard uses proprietary firmware and is not compatible with QMK. It's a complete product, not an open-source keyboard kit.

### Can I modify the hardware?
While technically possible for advanced users, hardware modifications will void any warranty and are not recommended or supported.

---

## Tips and Best Practices

### What's the best way to organize my configurations?
- Create separate profiles for different applications
- Name profiles clearly (e.g., "Photoshop_Editing", "Gaming_FPS")
- Document your setups
- Back up your configuration files regularly

### How should I clean the keyboard?
- Unplug before cleaning
- Use compressed air for dust
- Wipe with slightly damp cloth (not wet!)
- Never submerge in liquid
- Clean regularly to maintain performance

### Any ergonomic tips?
- Position the keyboard within easy reach
- Don't strain to press keys
- Consider your most-used functions when mapping keys
- Take breaks during extended use

---

## Still Have Questions?

- Check the [README.md](README.md) for general information
- See [QUICK_START.md](QUICK_START.md) for setup guide
- Review [TROUBLESHOOTING.md](TROUBLESHOOTING.md) for problems
- Browse [USE_CASES.md](USE_CASES.md) for configuration ideas
- Open an issue in this repository for documentation questions
- Contact GEEKRIA support for product-specific questions

---

*This FAQ is community-maintained. Have a question that's not answered here? Feel free to contribute!*

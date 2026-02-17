# Troubleshooting Guide

This guide covers common issues and their solutions for the GEEKRIA Mini Macro Keyboard.

## Table of Contents
- [Hardware Issues](#hardware-issues)
- [Software Issues](#software-issues)
- [Configuration Issues](#configuration-issues)
- [Operating System Specific](#operating-system-specific)

---

## Hardware Issues

### Keyboard Not Lighting Up

**Symptoms:** No LED lights when plugged in, keys don't respond

**Solutions:**
1. Try a different USB port on your computer
2. Test with a different USB cable (if available)
3. Try connecting to another computer to isolate the issue
4. Check if the USB port provides enough power (use a direct port, not a hub)
5. Inspect the cable for any visible damage

### Keys Not Responding

**Symptoms:** LED lights work but key presses don't register

**Solutions:**
1. Disconnect and reconnect the keyboard
2. Try a different USB port
3. Restart your computer
4. Check if the configuration software shows the keyboard as connected
5. Reset to default settings using the configuration software

### Knob Not Working

**Symptoms:** Rotation or press of the knob doesn't register

**Solutions:**
1. Verify the knob function in the configuration software
2. Test the default function (volume control)
3. Make sure no conflicting software is intercepting the signals
4. Try reconfiguring the knob in the software
5. Restart the computer with the keyboard connected

### Intermittent Connection

**Symptoms:** Keyboard randomly disconnects or stops responding

**Solutions:**
1. Check for loose cable connections
2. Use a different USB port (avoid USB hubs)
3. Update your USB drivers
4. Disable USB power saving in Windows:
   - Device Manager → USB Root Hub → Power Management
   - Uncheck "Allow computer to turn off this device"
5. Try a different USB cable

---

## Software Issues

### Configuration Software Won't Launch (Windows)

**Solutions:**

1. **Run as Administrator**
   - Right-click `MINI_KEYBOARD.exe`
   - Select "Run as administrator"

2. **Antivirus Blocking**
   - Add the software folder to your antivirus exceptions
   - Temporarily disable antivirus to test
   - This is a false positive - the software is safe

3. **Missing Dependencies**
   - Install Visual C++ Redistributable:
     - Download from Microsoft's website
     - Install both x86 and x64 versions
   - Install .NET Framework (if prompted)

4. **Windows Defender SmartScreen**
   - Click "More info" when blocked
   - Click "Run anyway"

5. **Compatibility Mode**
   - Right-click `MINI_KEYBOARD.exe` → Properties
   - Go to Compatibility tab
   - Try "Windows 7" or "Windows 8" compatibility mode

### Configuration Software Won't Launch (MacOS)

**Solutions:**

1. **Security Settings**
   ```
   System Preferences → Security & Privacy → General
   Click "Open Anyway" next to the blocked message
   ```

2. **Reinstall Package**
   - Delete any existing installation
   - Reinstall `MINI_KEYBOARD.pkg`
   - Enter admin password when prompted

3. **Check Permissions**
   ```
   System Preferences → Security & Privacy → Privacy
   Make sure MINI_KEYBOARD has necessary permissions
   ```

4. **Gatekeeper Override** (Advanced)
   ```
   Terminal: sudo spctl --master-disable
   Install the software
   Re-enable: sudo spctl --master-enable
   ```

### Software Crashes When Saving Configuration

**Solutions:**
1. Close and restart the software
2. Try configuring one key at a time
3. Check for system updates
4. Reinstall the software
5. Make sure no other keyboard software is running

### Configuration Not Saving

**Solutions:**
1. Run software as Administrator (Windows) or with sudo (MacOS)
2. Make sure keyboard is connected when saving
3. Try disconnecting and reconnecting after saving
4. Check file permissions in the software folder
5. Reinstall the software in a different location

---

## Configuration Issues

### Keys Execute Wrong Commands

**Solutions:**
1. Open configuration software and verify settings
2. Clear all configurations and reconfigure
3. Make sure you clicked "Save" or "Apply"
4. Restart the keyboard (disconnect/reconnect)
5. Try resetting to factory defaults

### Macros Not Working Properly

**Solutions:**
1. Increase delay between macro commands (if available)
2. Test with simple macros first (2-3 keys)
3. Make sure target application is in focus
4. Some applications may block macro inputs for security
5. Try recording the macro again

### LED Not Changing/Not Working

**Solutions:**
1. Check LED settings in configuration software
2. Some configurations may disable LEDs
3. Reset to default to restore LED functionality
4. Try different LED modes
5. Verify power supply is adequate

### Can't Reset to Default Settings

**Solutions:**
1. Look for "Reset" or "Default" button in software
2. Uninstall and reinstall the configuration software
3. Try holding specific key combination while plugging in (check manual)
4. Contact support for factory reset procedure

---

## Operating System Specific

### Windows 11 Specific Issues

**Issue:** Keyboard not recognized

**Solutions:**
1. Update Windows to latest version
2. Check Device Manager for driver warnings
3. Install latest USB drivers from motherboard manufacturer
4. Try disabling fast startup:
   ```
   Control Panel → Power Options → Choose what power buttons do
   Uncheck "Turn on fast startup"
   ```

### MacOS Monterey/Ventura Issues

**Issue:** Permissions errors or software won't run

**Solutions:**
1. Grant Input Monitoring permission:
   ```
   System Preferences → Security & Privacy → Privacy → Input Monitoring
   Add MINI_KEYBOARD to the list
   ```

2. Grant Accessibility permission:
   ```
   System Preferences → Security & Privacy → Privacy → Accessibility
   Add MINI_KEYBOARD to the list
   ```

3. Allow keyboard access:
   ```
   System Preferences → Keyboard → Keyboard Shortcuts
   Make sure shortcuts aren't conflicting
   ```

### Linux Support

**Note:** This keyboard is designed for Windows and MacOS. Linux support is limited.

**Partial Support:**
- Basic key presses should work with USB HID
- Configuration software may not work
- Alternative: Use QMK or similar firmware (requires advanced knowledge)

---

## Still Having Issues?

### Before Contacting Support

1. ✅ Tried all relevant solutions above
2. ✅ Tested on a different computer
3. ✅ Tried a different USB cable
4. ✅ Updated operating system
5. ✅ Reinstalled configuration software

### Information to Provide

When seeking help, include:
- Operating system and version
- Exact error message or behavior
- Steps you've already tried
- When the issue started
- Whether it ever worked correctly

### Support Resources

- Product warranty: Through place of purchase
- GEEKRIA support: Contact manufacturer
- Community help: Check online forums for macro keyboard users
- This repository: Open an issue for documentation problems

---

## Prevention Tips

1. **Always safely eject** - Don't just unplug the keyboard
2. **Keep software updated** - Install updates when available
3. **Regular backups** - Save your key configurations
4. **Avoid USB hubs** - Connect directly to computer when possible
5. **Clean regularly** - Dust can affect performance
6. **Handle cable carefully** - Don't stress the connection points

---

## Quick Fixes Checklist

Try these in order:

- [ ] Disconnect and reconnect keyboard
- [ ] Restart computer
- [ ] Try different USB port
- [ ] Run configuration software as Admin
- [ ] Reset to default settings
- [ ] Reinstall configuration software
- [ ] Test on different computer
- [ ] Check for OS updates
- [ ] Disable antivirus temporarily
- [ ] Read relevant section above

---

*Last updated: 2026-02*

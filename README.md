# FlooCast - Precompiled

A Pre-built Python application that allows for the control and configuration of FlooGoo USB Bluetooth dongles.

It configures a FlooGoo FMA120 Bluetooth dongle to pair and connect with a Bluetooth headset/speaker for streaming audio or making VoIP calls. It can also configure the dongle to work as an AuraCast sender.

The dongle functions as a standard USB audio speaker and microphone, requiring no drivers on Windows, macOS, or Linux.

## Installation

This repository hosts prebuilt application for various platforms below:

- Windows (x86)
- Linux (x86_64)
- macOS (arm64 - Apple Silicon & x86_64 - Intel)

You can download pre-compiled applicaion at [release tab.](https://github.com/potatosalad775/FlooCast/releases)

On Windows, the compiled App can also be downloaded directly from [Microsoft Store.](https://apps.microsoft.com/detail/9nx1cw8vz6qr)

## Usage

Once configured, the dongle can automatically reconnect to the most recently used device. Please check the support link for more advanced uses. 
 
## Platform specific notes/issues

On Linux, if you run the app as a non-root user, you might get "Permission denied: '/dev/ttyACM0'" error. 
Please verify the ttyACM0 device is the "dialout" user group and add your $USER to the group.
You may take the following link as a reference,
https://askubuntu.com/questions/133235/how-do-i-allow-non-root-access-to-ttyusb0

## Acknowledgements


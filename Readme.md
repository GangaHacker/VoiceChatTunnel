# VCT (Voice Chat Tunnel) - GangaHacker's Fork

This is a fork of Kemo's Voice Chat Tunnel (VCT) project, with bug fixes, minor feature enhancements, and quality-of-life improvements. The original project provides a simple VPN solution optimized for voice chat applications like Discord, prioritizing low latency connections.

## Changes in this Fork

* **Fixed:** Crash on startup when the servers list couldn't be retrieved.
* **Fixed:** Issue where the VPN wouldn't disconnect properly under certain conditions.
* **Improved:** Clarity of connection status messages.
* **Added:** Tooltips to clarify the functionality of UI elements.
* **Added:** Ping to servers and score display for better server selection.


## Features

* **Automatic Server Selection:** VCT automatically selects a VPN server optimized for low latency, ideal for voice chat.
* **Easy-to-Use Interface:** A simple and clean GUI makes connecting and disconnecting a breeze.
* **Minimizes to Tray:** Keeps VCT running discreetly in the background.
* **Auto-Startup Option:** Configure VCT to start automatically with Windows.
* **Discord Integration:** A quick link to join the VCT Discord server for support and community interaction.

## How to Use

1. **Download:** Download the latest release from the [Releases](Releases_Link_Here) section.
2. **Extract:** Extract the downloaded zip file.
3. **Run:** Execute the `VCT.exe` file.
4. **Connect:** Click the power button in the main window to connect to the selected VPN server.
5. **Disconnect:** Click the power button again to disconnect.

## Configuration

VCT currently doesn't offer extensive configuration options. The focus is on simplicity and ease of use. Future updates may include more customizable settings.

## Building from Source (For Developers)

1. **Clone the Repository:** `git clone https://github.com/GangaHacker5/VCT`
2. **Dependencies:**  [List specific dependencies and versions here]
3. **Build:** Open the solution in Visual Studio and build the project.


## Troubleshooting

* **Connection Issues:** If you're unable to connect, ensure you have a stable internet connection. Try restarting VCT or your computer. Check firewall settings.
* **Disconnection Issues:** If VCT doesn't disconnect cleanly, try manually disconnecting through the Windows network settings.
* **"Already Connected" Error:** If you receive this error, make sure any previous VCT connections are closed.
* **No Servers Found:** Verify your internet connection and try refreshing the server list. Consider temporarily disabling firewall or antivirus software.

## Known Issues

* The application may not disconnect properly if the VPN adapter was already active before VCT was launched. A workaround is to manually disconnect the VPN through Windows settings before starting VCT.

[Include a screenshot or GIF here]

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements, feel free to open an issue or submit a pull request.


## Credits

* **Original Creator:** Kemo (@xkem0x on Twitter)
* **This Fork Maintainer:** GangaHacker5
* **README Assistance:** Gemini 1.5 Pro 002
* **Special Thanks:**
    * GangaHacker for editing and improvements
    * Defaults, Ramy (@RamyWafik on Twitter)
    * MadTitan (@MadTitan__ on Twitter)
    * Sohila (@ananaymabye on Twitter)


## License



## Disclaimer

Use this software responsibly. Be aware of the terms of service of any online platforms you use while connected to the VPN. The maintainers of this fork are not responsible for any misuse of this software.


## Future Development

* Improved server selection algorithms based on ping and other factors.
* Customizable settings for more advanced users.

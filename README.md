# Fix Touchpad Scaling Issue: Convert Pinch to Scroll

[![GitHub release](https://img.shields.io/github/v/release/inetkachev/Fix-touch.svg)](https://github.com/inetkachev/Fix-touch/releases)
[![License](https://img.shields.io/github/license/inetkachev/Fix-touch)](LICENSE)

**Fix Touchpad Scaling Issue** is a lightweight utility designed to solve a common problem with some Windows touchpads that mistakenly send pinch-to-zoom events instead of scroll events. This tool intercepts pinch gestures and converts them into smooth scroll actions, improving user experience for those with glitchy touchpads.

## Features

- **Block Pinch-to-Zoom Events**: Automatically converts pinch-to-zoom gestures into scroll events.
- **Runs in Background**: Works silently without any interface, consuming minimal system resources.
- **Simple Setup**: Just download, run, and enjoy a smoother touchpad experience.
- **Customizable**: Easily extend or modify the behavior for other specific needs.

## Why This Tool?

Many Windows touchpad users face issues where touchpad gestures meant for scrolling are incorrectly interpreted as pinch-to-zoom gestures, leading to frustrating zooming instead of scrolling. This utility is designed to solve this problem by blocking pinch gestures and replacing them with smooth scroll actions.

## ATTENTION

It will destroy CTRL+MouseWheel ZOOM at all. 

## Installation

### 1. Download the Latest Release

Head to the [releases page](https://github.com/inetkachev/Fix-touch/releases) and download the latest version of **Fix Touchpad Scaling Issue**.

- **Framework-dependent version** (requires .NET runtime installed)

### 2. Run the Program

Once downloaded, unzip the archive and run the `.exe` file. The program will start in the background and automatically block pinch-to-zoom events on your touchpad.

No installation or configuration is needed. To stop the program, simply close it from the task manager.

For autorun make shortcut and put it to shell:startup (it's folder)

## Requirements

- Windows 10/11
- **For Framework-dependent version**: [.NET Runtime](https://dotnet.microsoft.com/download) (if not already installed)

## Contributing

Contributions are welcome! If you have any suggestions or improvements, feel free to open an issue or submit a pull request. 

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Support

If you encounter any issues or have questions, feel free to open an [issue on GitHub](https://github.com/yourusername/yourproject/issues).

---

### Keywords:
- Fix touchpad scaling issue
- Block pinch-to-zoom on Windows
- Convert pinch to scroll Windows
- Windows touchpad zoom problem
- Disable pinch gestures
- Touchpad scroll fix

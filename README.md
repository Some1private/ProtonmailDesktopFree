# ProtonmailDesktopFree

Protonmail "developed" their own paid desktop application using electron, which took me 5 minutes to create with electron but it was detected by protonmail and I couldn't bypass the paywall.

So I created another desktop protonmail application using Tauri. 

```markdown
# ProtonMail Desktop

An open-source, unofficial desktop application for ProtonMail built using Tauri.

## Description

This project is a lightweight, cross-platform desktop application that wraps the ProtonMail web interface. It provides a native-like experience for ProtonMail users on desktop operating systems.

## Features

- Native desktop application experience for ProtonMail
- Cross-platform support (Windows, macOS, Linux)
- Lightweight and fast, powered by Tauri

## Installation

1. Go to the [Releases](https://github.com/yourusername/protonmail-desktop/releases) page.
2. Download the appropriate version for your operating system.
3. Install the application following your OS-specific installation process.

## Building from Source

To build the application from source, follow these steps:

1. Ensure you have [Node.js](https://nodejs.org/) and [Rust](https://www.rust-lang.org/tools/install) installed.

2. Clone the repository:
   ```
   git clone https://github.com/yourusername/protonmail-desktop.git
   cd protonmail-desktop
   ```

3. Install dependencies:
   ```
   npm install
   ```

4. Run the development version:
   ```
   npm run tauri dev
   ```

5. Build the production version:
   ```
   npm run tauri build
   ```

   The built application will be in the `src-tauri/target/release` directory.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Disclaimer

This is an unofficial, open-source project and is not affiliated with Proton Technologies AG.

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

For support, please open an issue on the GitHub repository.
```

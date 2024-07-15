# ProtonmailDesktopFree

Protonmail "developed" their own paid desktop application using electron, which took me 5 minutes to create with electron but it was detected by protonmail and I couldn't bypass the paywall.

So I created another desktop protonmail application using Tauri. 

An open-source, unofficial desktop application for ProtonMail built using Tauri.

## Description

This project is a lightweight, Windows desktop application that wraps the ProtonMail web interface. It provides a native-like experience for ProtonMail users on desktop operating systems.

## Features

- Native desktop application experience for ProtonMail
- Lightweight and fast, powered by Tauri
- Supports notifications
- Portable and install versions available

## Installation

1. Go to the [Releases](https://github.com/Some1private/ProtonmailDesktopFree/releases) page.
2. Download the application and install it or alternatively download the portable version and launch it right away.

## Building from Source

To build the application from source, follow these steps:

1. Ensure you have [Node.js](https://nodejs.org/) and [Rust](https://www.rust-lang.org/tools/install) installed.

2. Clone the repository:
   ```
   git clone https://github.com/Some1private/ProtonmailDesktopFree.git
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

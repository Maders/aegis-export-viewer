# Aegis Authenticator Unencrypted Export File Viewer

This repository contains a simple web-based viewer for unencrypted export files generated by the Aegis Authenticator app. The viewer allows you to load an Aegis Authenticator export file in JSON format and display the stored entries along with their corresponding OTP QR codes.

## Overview

The Aegis Authenticator app allows users to export their OTP entries to a JSON file. This viewer provides a convenient way to visualize the entries and generate QR codes for the OTPs.

## Features

- Load Aegis Authenticator export files in JSON format.
- Display OTP entries along with their names.
- Generate QR codes for each entry's OTP information.
- Entries are shown as a list with the corresponding QR codes displayed above the entry names.

## Usage

1. Clone or download this repository to your local machine.
2. Open the `index.html` file in a web browser.
3. Click the "Choose File" button to select the Aegis Authenticator export file (in JSON format) you want to view.
4. The viewer will display the OTP entries with their names and QR codes.

## Dependencies

- [qrcode.js](https://davidshimjs.github.io/qrcodejs/) - Used to generate QR codes for OTP information.

## Compatibility

The viewer is designed to work in modern web browsers. It doesn't require any server-side setup and can be run locally.

## Contributing

Contributions are welcome! Feel free to open issues for bug reports, feature requests, or submit pull requests for improvements.

## Disclaimer

This viewer is provided as-is and is not affiliated with the Aegis Authenticator app's developers. Use it at your own risk. **Ensure you're handling your sensitive data securely**.

---

**Note:** This viewer is for unencrypted export files only. It won't work with encrypted backup files from the Aegis Authenticator app.

For more information about the Aegis Authenticator app, visit their official website: [Aegis Authenticator](https://getaegis.app/)

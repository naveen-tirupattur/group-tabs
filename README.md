# TabZen Chrome Extension

This is a Chrome extension that allows you to group tabs by domain name. 
It provides the option to group/ungroup tabs either in the active window or across all windows.

## Features

- Group tabs by domain name.
- Select between grouping/ungrouping tabs in the active window or across all windows.

## Installation

To install the extension, follow these steps:

1. Clone or download this repository to your local machine.
2. Open Google Chrome and go to `chrome://extensions`.
3. Enable Developer mode by toggling the switch in the top right corner.
4. Click on "Load unpacked" and select the directory where you saved the extension files.
5. The extension should now be loaded and ready to use.

## Usage

1. Click on the extension button in the Chrome toolbar.
2. A popup window will appear with options to group and ungroup tabs.
3. Select the desired action:
   - **Group Tabs (Active Window):** Group tabs within the active window by domain name.
   - **Group Tabs (All Windows):** Group tabs across all open windows by domain name.
   - **Ungroup Tabs (Active Window):** Ungroup tabs within the active window.
   - **Ungroup Tabs (All Windows):** Ungroup tabs across all open windows.

## Folder Structure

- `background.js`: Contains the background script that handles tab grouping and ungrouping.
- `popup.html`: Represents the HTML content for the popup window that appears when the extension button is clicked.
- `popup.js`: Provides the JavaScript functionality for the popup window.
- `manifest.json`: Defines the metadata and configuration for the Chrome extension.
- `LICENSE`: The license file specifying the GNU General Public License (GPL) terms.

## Customization

This extension provides a basic implementation for tab grouping by domain name. You can customize and enhance the code to suit your specific needs. Some possible enhancements include:

- Adding additional grouping or ungrouping options.
- Implementing advanced tab management features.
- Customizing the extension's appearance and behavior.

Feel free to explore the code and make modifications according to your requirements.

## License

This project is licensed under the [GNU General Public License v3.0](LICENSE).

## Disclaimer

This extension is provided as-is without any warranty. Use it at your own risk.

## Contributing

Contributions are welcome! If you have any ideas, improvements, or bug fixes, please submit a pull request or open an issue.

## Credits

This extension was developed by Naveen Tirupattur

## Contact

For any inquiries or questions, please contact naveen.tirupattur@gmail.com

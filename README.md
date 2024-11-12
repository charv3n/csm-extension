# Snippet Manager

A Chrome extension to save, manage, and quickly access code snippets directly from your browser. Perfect for developers who want a simple, local solution to organize frequently used snippets and copy them to the clipboard with ease.

## Features

- Save code snippets with a single click
- View saved snippets in an organized list
- Copy snippets to the clipboard directly from the extension
- Lightweight and easy to use, with local storage for privacy

## Installation
Open Chrome Extensions page:

Go to chrome://extensions in your Chrome browser.
Enable Developer Mode:

Toggle on Developer Mode in the top-right corner of the page.
Load the Unpacked Extension:

Click Load unpacked and select the snippet-manager folder that you cloned or downloaded.
Verify Installation:

The extension icon should appear in your Chrome toolbar.
Usage
Click the Snippet Manager icon in your Chrome toolbar to open the popup.
Enter a code snippet in the text area and click Save Snippet to add it to the list.
Saved snippets are displayed in the popup below the input area.
To copy a snippet, click the Copy button next to it. This copies the snippet to your clipboard for easy pasting.
You can close and reopen the popup as needed, and your snippets will remain saved.
Project Structure
1. **Clone or download this repository**:
   ```bash
   git clone https://github.com/your-username/snippet-manager.git

   snippet-manager/
├── manifest.json       # Defines extension's properties and permissions
├── popup.html          # UI for the extension
├── popup.js            # JavaScript for snippet saving, loading, and copying
├── style.css           # Basic styling for the popup UI
└── icons/              # Folder containing icons for the extension


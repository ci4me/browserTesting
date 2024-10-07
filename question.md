# Request to Build a Chrome Extension: AIChatsExtended

**Objective:**
Please build a Chrome extension named "AIChatsExtended" that enhances AI chat pages functionalities with advanced file management features. I want this extension to work on chatGpt.com, DeepSeeker.com and https://openrouter.ai/chat. The main feature of this extension is to detect when a file is sent in the AI chat ui. We should monitor both, the DOM and the network to check for new files.

The extension needs adjust/change the user message to include some instructions, something like: Please, whenever you generate a file add a comment on the first line with some json data included. Start of the File, The file full name. The date and time it was generated. Add a comment on the last line with some json data included. End of File, The file full name. The date and time it was generated. Also add something to prevent code snippets or incomplete code. Example, when chatGtp says: for brevity... or Other Functions go here...

If it is a incomplete file, can we get the data from the last one and merge ? Or ask the chat to send the complete file.

The extension should have a list of all files generated. It should give the option to download the file.

The extension must have a button to Download All files as Zip using the JsZIP javascript library.

All the assets must be included in the extension and do not be loaded in CDN.

The extension should include the following functionalities:

1. **File Version Comparison**: Allow users to compare different versions of files using the ACE editor
2. **Code Viewer**: Enable users to view code in a new tab using the ACE Editor.
3. **Encryption Utilities**: Provide functions to encrypt and decrypt data using AES-GCM.
4. **Message Detection**: Monitor chat windows for new messages and notify the user.
5. **Popup UI**: Create a user-friendly popup UI with buttons for uploading files, backing up data, restoring data, and saving settings.
6. **Options Page**: Include an options page for managing extension settings.
7. **Styling**: Use Semantic UI for styling the GUI.

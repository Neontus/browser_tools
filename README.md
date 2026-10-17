# browser_tools

Personal tools for making Brave more useful for AI assisted work and tab management.

## Direction

Start as a standalone Chromium extension for Brave. Brave supports Chromium extensions, and the extension APIs cover tabs and tab groups. Keeping this separate from Brave's browser source makes it practical to install and iterate on personal workflows without maintaining a custom browser build.

Potential features:

- Select and organize browser context for AI tasks.
- Hand selected context to a local Codex workflow, subject to the APIs and permissions available at implementation time.
- Manage tabs and groups, including grouping, moving, and restoring work sessions.

If a desired feature requires modifying Brave internals or APIs unavailable to extensions, evaluate a targeted `brave-core` contribution or fork for that feature.

## Status

Repository setup and project direction. No extension code has been implemented yet.

## References

- [Brave extension support](https://support.brave.com/hc/en-us/articles/360017909112-How-can-I-add-extensions-to-Brave)
- [Chromium extension tabs API](https://developer.chrome.com/docs/extensions/reference/api/tabs)
- [Chromium extension tab groups API](https://developer.chrome.com/docs/extensions/reference/api/tabGroups)
- [Chromium native messaging](https://developer.chrome.com/docs/extensions/develop/concepts/native-messaging)
- [Brave Core](https://github.com/brave/brave-core)

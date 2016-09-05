# Chrome Type Ahead

I found this extension code on GitHub and cloned it from https://github.com/tokland/chrome-type-ahead

This was an exported project form Google Code https://code.google.com/archive/p/chrome-type-ahead/

## Original README from Google Code

### Motivation

Type-ahead-find (or find as you type) is an extremely useful accessibility feature (a core functionality in major browsers like Firefox or Safari), but it's not implemented in Chrome (nor planned to be).

### Status

The extension covers the goals I had when I start writing it, so its status is "maintenance-only mode". Fully functional patches are welcome, though.

### Notes

- Start writing (or press /) to start text search.
- Press ' to search only links.
- Use F3 or Control+G or Alt+N/P to switch between matches.
- Use F4 to toggle matching mode (text/links) once the search has started.
- Blacklist support for sites that set up their own shortcuts.
- Search and select options in HTML selects (disabled by default).

### Download

[Download the extension.](https://chrome.google.com/extensions/detail/cpecbmjeidppdiampimghndkikcmoadk)

### How to install the extension from sources

First of all, read ***this page*** *(sadly the link doesn't seem to be point to anything on the Google Code project)*. Then:

1. Checkout code: svn checkout http://chrome-type-ahead.googlecode.com/svn/trunk/ chrome-type-ahead
1. Open Extensions page in Chrome.
1. Disable old installed versions of the extension.
1. Enable developer mode.
1. Press button load uncompressed extension.
1. Select the directory where you checked out the code to.

And that's it. Note that extensions installed that way provide a link to reload them easily.

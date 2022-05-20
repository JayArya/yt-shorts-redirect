# yt-shorts-redirect

Youtube UX on the desktop throws me off personally because of the introduction of YT Shorts.

This extension simply redirects every request from YT Shorts format to the regular Youtube videos.

This extension uses the [chrome.declarativeNetRequest API](https://developer.chrome.com/docs/extensions/reference/declarativeNetRequest/ "API Reference") to modify network requests by specifying declarative rules. This lets the extension modify network requests without intercepting them and viewing their content, thus providing more privacy.

Due to the limitation of chrome.declarativeNetRequest the extension only works for new page requests(that is, it only works if the video is opened in a new tab).

### Steps to use this Extension
1. Download the "index.html", "manifest.json", "rules.json" files into a new directory named **yt-shorts-redirect**
2. Open Chrome Extensions Menu: [Click Here](chrome://extensions/) **OR** Chrome Menu(Right hand 3 dots icon) -> Select More Tools -> Extensions
3. Enable Developer Mode (Toggle on Top-Right Side)
4. Click Load Unpacked Button
5. Navigate to the **yt-shorts-directory** and select the entire folder.
6. Enable the extension
7. Don't need to do anything else. The YT Shorts video will be redirected automatically

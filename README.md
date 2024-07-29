# Picture-in-Picture Hack Bookmarklet

This repository contains a simple JavaScript bookmarklet that enables Picture-in-Picture (PiP) mode on websites that normally disallow this feature.

## Installation Instructions

1. Create a new bookmark in your Chrome browser.
2. Name the bookmark "PiP Hack" (or any name you prefer).
3. In the URL field, paste the following code:
    `javascript:var video=document.getElementsByTagName('video');video.removeAttribute('disablePictureInPicture');video.requestPictureInPicture()`
4. Save the bookmark.

## Usage

1. Navigate to a video website that disables PiP.
2. Click on the "PiP Hack" bookmark you created.
3. The video should now enter Picture-in-Picture mode.

## Important Notice
This hack is not recommended for regular use due to the following reasons:
1. It bypasses website restrictions, which may violate terms of service.
2. Captions do not appear in the PiP window, making it inaccessible for users who rely on captions.
3. Some streaming platforms, like Hulu, intentionally disable PiP to ensure a complete viewing experience, including captions and interactive elements.
Use this hack responsibly and be aware of potential limitations and legal implications.

## Disclaimer
This bookmarklet is provided for educational purposes only. Use at your own risk and respect the terms of service of the websites you visit.

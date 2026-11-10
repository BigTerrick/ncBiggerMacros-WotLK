# ncBiggerMacros-WotLK

A copy of **ncBiggerMacros** for **WoW 3.3.5a (Wrath of the Lich King)** private servers such as ChromieCraft, with a fix for `#showtooltip` on long macros.

ncBiggerMacros is a little addon that lets you create macros up to **1024 characters** long, right in the default macro window. That's all it does.

## Credit

- **nightcracker** is the original author of ncBiggerMacros. All credit for the addon goes to him.
  - Original download: <https://www.wowinterface.com/downloads/info16503-ncBiggerMacros.html>
- **MaXiMiUS** wrote the `#showtooltip` fix included in this repo, posted in the comments on the WoWInterface page on 07-19-10.

The first commit in this repo is the unmodified v1.2 BETA download from WoWInterface. The second commit adds MaXiMiUS's fix.

## What the fix does

Macros over 255 characters are stored by the addon and run through a short `/click` macro. As a result, `#showtooltip` and `#show` lines were lost and the macro icon showed no tooltip. With the fix, a `#show` or `#showtooltip` line at the start of the macro is kept in the short macro that WoW reads, so the tooltip works again.

**Please back up your macros before using this addon, and use it at your own risk.** Your macro files are in your `WTF` folder (`macros-cache.txt`, in the account and character folders).

## Usage

Install and go. There is no configuration and there are no slash commands. Open the macro window as usual and the macro text box accepts up to 1024 characters.

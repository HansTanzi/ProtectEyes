# ProtectEyes

English | [简体中文](./README.zh-CN.md)

> [!WARNING]
> **This project is no longer maintained.** It has been superseded by [RestGuard](https://github.com/HansTanzi/RestGuard/).

**About**: A timed pop-up that forces you to take breaks — protect your eyes and avoid overwork.
* It's called a "forced break" because it can't be closed through normal means.
* With a bit of effort it can still be closed, e.g. by restarting the computer or killing it in Task Manager.

![Screenshot](./Image/效果图.png)

## Environment

VS2015, Windows 7

## Usage

Run `Bin\设置开机自启.bat` (Set auto-start on boot) to copy the program to the C drive and register it to start automatically at boot.

Once running, a pop-up window appears every hour and starts a countdown. Until the countdown ends, the window cannot be closed, moved, or resized.

## Roadmap

I may not get around to these myself — contributions are welcome:
1. Expose the break time and work time as settings in a config file (not in the UI, otherwise it wouldn't be a forced break anymore).
2. Add animations and some friendly tips to the main window.

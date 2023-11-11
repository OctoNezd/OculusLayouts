# Extra Oculus Keyboard Layouts

Modified version of https://android.googlesource.com/platform/frameworks/base/+/refs/heads/android12--mainline-release/packages/InputDevices/

Changes:

-   Different app name and package id, to not conflict with built-in keyboard layouts

## Building

Build project in Android Studio

## Installation

Install using adb or any other way of sideloading apps onto Oculus Quest.

Go to (Quest) Settings -> Devices - Keyboard - Physical keyboard and add your desired layout.

Custom layouts have "Android Keyboard" as their provider

## Limitations

Doesn't work in Settings, Quest Browser, Feed and potentially other Meta apps. As a workaround for browser you can use Wolvic instead. I assume they force layout or handle keyboard events manually?

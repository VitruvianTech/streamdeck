# StreamDeck Scripts
A collection of PowerShell scripts, specifically for use as Elgato StreamDeck Open (System) files.

Below are example usages.

## Mute

This script toggles muting the default audio input device (microphone), resets the input volume to 100% (when unmuted), and presents a tooltip balloon indicating mute status.

`powershell -windowstyle hidden -ExecutionPolicy ByPass -File "C:\Program FIles\Elgato\StreamDeck\Scripts\mute.ps1"`

## VS Code

This script will open a specified VS Code project in a new window.

`powershell -windowstyle hidden -ExecutionPolicy ByPass -File "C:\Program FIles\Elgato\StreamDeck\Scripts\code.ps1" "C:\<Path-Code-Project>"`

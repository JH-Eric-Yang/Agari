# Agari

Agari is an application for researchers who study gesture and multimodal communication.
You organise your recordings. You align video, audio and transcripts on one timeline.
You mark time ranges. You fill a coding form for each range. You export the results.

This repository holds the installers of **Agari Desktop**, the version that runs on your own computer.

## Download

Go to the [latest release](https://github.com/JH-Eric-Yang/Agari/releases/latest) and download the file for your computer.

| Computer | File | Requirements |
| --- | --- | --- |
| Mac | `Agari-Desktop-<version>-arm64.dmg` | Apple silicon (M1 or later), macOS 13 Ventura or later |
| Windows | `Agari-Desktop-Setup-<version>-x64.exe` | 64-bit Intel or AMD processor, Windows 10 or 11 |

## Install on a Mac

1. Open the `.dmg` file.
2. Move **Agari Desktop** into the **Applications** folder.
3. Open **Agari Desktop** from the Applications folder.

The installers are not yet signed by Apple. macOS can refuse to open the app the first time. If it does:

1. Open **System Settings**.
2. Select **Privacy & Security**.
3. Find the message about Agari Desktop.
4. Select **Open Anyway**.

## Install on Windows

1. Open the `.exe` file.
2. Follow the steps of the installer.

The installers are not yet signed. Windows can show the message "Windows protected your PC". If it does:

1. Select **More info**.
2. Select **Run anyway**.

## Your data stays on your computer

Agari Desktop keeps your recordings, your projects and your coding on your computer.
It does not send them to a service.
The app uses the network only in these cases, and only when you ask:

- You download the speech models for automatic transcription. The app asks before it starts the download.
- You connect the app to an Agari server of your research group.

## Report a problem

Open an [issue](https://github.com/JH-Eric-Yang/Agari/issues).
Give the version of the app, your operating system and the steps that show the problem.
Do not attach recordings or data of participants.

## Third-party software

Agari Desktop includes FFmpeg, built under the LGPL, and whisper.cpp.
Each release includes the source archives of the FFmpeg and whisper.cpp versions in the installers.
The file `THIRD_PARTY_NOTICES.txt` in the app lists all third-party software and licences.

## Source code

The source code is not public yet.

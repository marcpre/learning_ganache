# learning_ganache

## Ganache UI under Windows 8.1

## 1. Download
Download Ganache UI from the [trufflesuite repo](https://github.com/trufflesuite/ganache/releases)

## 2. Install Windows 10 SKD

Download from [official page](https://developer.microsoft.com/en-us/windows/downloads/windows-10-sdk)

## 3. Unpack

You can find `makeappx.exe` in the folder: `C:\Program Files (x86)\Windows Kits\10\App Certification Kit`

Start `cmd` there.

## 4. Run the installed ganache-cli file with the cmd

`makeappx.exe unpack /p C:\Users\user_name\Desktop\Ethereum\Ganache.appx /d C:\Users\user_name\Desktop\Ethereum`

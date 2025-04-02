# Welcome To BypassNRO

This repository contans an archive of the Windows BypassNRO script. This is a script that allows you to bypass the internet/
Microsoft account during Windows setup. Microsoft is removing it, so I have made sure to archive it.

## How It Works

First, it uses ```@echo off``` to silence output, and then uses ```reg add HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\OOBE /v BypassNRO /t REG_DWORD /d 1 /f``` to actualy bypass the requirements.
It then uses ```shutdown /r /t 0``` to restart the PC.

# Enjoy!

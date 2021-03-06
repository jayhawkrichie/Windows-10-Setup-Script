<div align="center">
  <h1>Windows 10 Setup Script</h1>

"Windows 10 Setup Script" is a set of tweaks for OS fine-tuning and automating the routine tasks.
</div>

## Core features

- Set up Privacy & Telemetry;
- Turn off diagnostics tracking scheduled tasks;
- Set up UI & Personalization;
- Uninstall OneDrive "correctly";
- Interactive prompts;
- Change %TEMP% environment variable path to %SystemDrive%\Temp
- Change location of the user folders programmatically (without moving user files) within interactive menu using up/down arrows and Enter key to make a selection
  - "Desktop";
  - "Documents";
  - "Downloads";
  - "Music";
  - "Pictures"
  - "Videos.
- Uninstall UWP apps from all accounts with exception apps list with pop-up form written in WPF;
- Turn off Windows features;
- Remove Windows capabilities with pop-up form written in [WPF](https://github.com/farag2/Windows-10-Setup-Script/raw/master/Images/Img-3.png);
- Create a Windows cleaning up task in the Task Scheduler;
- Create tasks in the Task Scheduler to clear
  - %SystemRoot%\SoftwareDistribution\Download
  - %TEMP%
- Unpin all Start menu tiles;
- Pin shortcuts to Start menu using [syspin.exe](http://www.technosys.net/products/utils/pintotaskbar)
- Turn on Controlled folder access and add protected folders using dialog menu;
- Add exclusion folder from Microsoft Defender Antivirus scanning using dialog menu;
- Add exclusion file from Microsoft Defender Antivirus scanning using dialog menu;
- Refresh desktop icons, environment variables and taskbar without restarting File Explorer;
- Many more File Explorer and context menu "deep" tweaks.

## Images

<details>
  <summary>Images and the GIF</summary>

  ![intro](https://github.com/farag2/Windows-10-Setup-Script/raw/master/Images/intro.gif)
  ![intro](https://github.com/farag2/Windows-10-Setup-Script/raw/master/Images/img-2.png)
  ![intro](https://github.com/farag2/Windows-10-Setup-Script/raw/master/Images/Img-3.png)
  ![intro](https://github.com/farag2/Windows-10-Setup-Script/blob/master/Images/GUI-1.png)
  ![intro](https://github.com/farag2/Windows-10-Setup-Script/blob/master/Images/GUI-2.png)
</details>

## Usage

To run the script:

- Download [up-to-date version](https://github.com/farag2/Setup-Windows-10/releases);
- Expand the archive;
- Check whether .ps1 is encoded in **UTF-8 with BOM**;
- Run Start.cmd as Administrator;
- The script will start immediately.

## Supported Windows versions

|Version|Code name|   Marketing name   |Build|  Arch  |      Editions     |
|:-----:|:-------:|:------------------:|:---:|:------:|:-----------------:|
| 1909  |  19H2   |November 2019 Update|18363|x64 only|Home/Pro/Enterprise|
| 1903  |  19H1   |   May 2019 Update  |18362|x64 only|Home/Pro/Enterprise|

## FAQ

Read the code you run carefully. Some functions are presented as an example only. You must be aware of the meaning of the functions in the code. **If you're not sure what the script does, do not run it**.
**Strongly recommended to run the script after fresh installation**. Some of functions can be run also on LTSB/LTSC and on older versions of Windows and PowerShell (not recommended to run on the x86 systems).

## GUI version (C#)

Still [Cooking](https://github.com/farag2/Windows-10-Setup-Script/tree/GUI-dev)

## Microsoft Docs

- [Release information](https://docs.microsoft.com/en-us/windows/release-information)
- [Known issues](https://docs.microsoft.com/en-us/windows/release-information/status-windows-10-1909)

## Ask a question on

- [Habr](https://habr.com/en/post/465365/)
- [Ru-Board](http://forum.ru-board.com/topic.cgi?forum=62&topic=30617#15)
- [4PDA](https://4pda.ru/forum/index.php?s=&showtopic=523489&view=findpost&p=95909388)
- [My Digital Life](https://forums.mydigitallife.net/threads/powershell-script-setup-windows-10.81675/)
- [Reddit](https://www.reddit.com/r/PowerShell/comments/go2n5v/powershell_script_setup_windows_10/)

## PS

Collection of useful [scripts](https://github.com/farag2/Utilities)

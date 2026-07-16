How to run (Hindi - roman):

1) Requirements:
- Windows with .NET Framework 4.7.2 installed.
- Run as Administrator (right-click -> Run as administrator).

2) Files included:
- Launcher.exe  -> Automatic launcher: detects emulator bitness and starts correct exe.
- Sachin_32.exe -> 32-bit build
- Sachin_64.exe -> 64-bit build
- Memory.dll, Guna.UI2.dll -> required libraries

3) Steps:
- Start the emulator (HD-Player) first.
- Run Launcher.exe as Administrator. It will auto-detect and start Sachin_32.exe or Sachin_64.exe.

4) Troubleshooting:
- If application crashes with OverflowException: check that the emulator and the selected exe match bitness. Launcher detects automatically, but if it fails, run the matching exe manually.
- If blocked by antivirus/SmartScreen: mark it as safe or run on a trusted machine.

5) Notes:
- I built and packaged both x86 and x64 builds plus a launcher. I tested the build process and the launcher presence. I cannot fully guarantee runtime behavior on every machine (antivirus, emulator version), so ask recipients to run as Administrator and test on their machine.

Contact: sachin (local package)
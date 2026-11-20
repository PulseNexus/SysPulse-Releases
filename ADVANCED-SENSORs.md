[ADVANCED-SENSORS.md](https://github.com/user-attachments/files/35178484/ADVANCED-SENSORS.md)
# Optional SysPulse Advanced Sensor Helper for Windows x64

This ZIP contains the SysPulse-specific helper and license materials. Obtain
LibreHardwareMonitor and, if needed, the signed PawnIO installer directly from
their publishers. Installing either dependency alone does not install the SysPulse helper.

1. Exit SysPulse from its tray menu. Open the folder containing `SysPulse.exe`.
   If `vendor\LibreHardwareMonitor` already exists, back it up outside the application
   folder before changing it.
2. Download **LibreHardwareMonitor.zip** from the [official v0.9.6 release](https://github.com/LibreHardwareMonitor/LibreHardwareMonitor/releases/tag/v0.9.6).
   Choose that asset for the .NET Framework build. Its SHA-256 is
   `086d9f1b5a99e643edc2cfaaac16051685b551e4c5ac0b32a57c58c0e529c001`.
   Extract it into `vendor\LibreHardwareMonitor` next to `SysPulse.exe`.
   Keep the upstream DLLs together so the library can resolve its dependencies.
3. Copy the supplied `SysPulseSensorHelper.exe` into that same folder, beside
   `LibreHardwareMonitorLib.dll`. No need to run the helper directly.
4. Where kernel sensor access is needed, obtain [PawnIO 2.2.0 Setup](https://github.com/namazso/PawnIO.Setup/releases/tag/2.2.0)
   or an upstream-supported compatible version from [pawnio.eu](https://pawnio.eu/).
   Use the official signed edition and check the installer's valid Windows
   signature before running it. SHA-256 for the official 2.2.0 installer is
   `1f519a22e47187f70a1379a48ca604981c4fcf694f4e65b734aaa74a9fba3032`.
   Driver installation requires administrator consent.
5. Reopen SysPulse, enable **Settings → Advanced sensor helper**, and approve
   the Windows prompt if you want to run it. If the helper is unavailable or the
   prompt is declined, affected readings remain unavailable. To remove the
   helper, disable it in Settings, exit SysPulse and remove the helper files
   you added, or restore your backup.

## Third-party notices and source access

- LibreHardwareMonitorLib v0.9.6 uses MPL-2.0 and includes components with
  additional terms. The corresponding [v0.9.6 source](https://github.com/LibreHardwareMonitor/LibreHardwareMonitor/tree/v0.9.6),
  MPL text and upstream notices identify those terms.
- The upstream LibreHardwareMonitor library includes signed PawnIO modules
  from [PawnIO.Modules 0.1.6](https://github.com/namazso/PawnIO.Modules/tree/0.1.6).
  The module license text is LGPL-2.1. The module source and build materials
  are in that tagged repository. See the LibreHardwareMonitor upstream module
  inventory in the included notices.
- The upstream [PawnIO 2.2.0 driver source](https://github.com/namazso/PawnIO/tree/2.2.0)
  carries GPL-2.0-or-later with an exception specified in its upstream README.
  The official signed installer is separately distributed by the publisher.

The `licenses` folder includes the upstream license texts and notices referenced
above. The SysPulse-specific helper is covered by the accompanying SysPulse LICENSE.

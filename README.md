
<div align="center">

# SysPulse

### Your system. Every detail.

A modern Windows application for hardware monitoring, system diagnostics, performance tracking, and incident analysis.

Developed by **Pulse**.

[![Download for Windows](https://img.shields.io/badge/Download_for_Windows-238636?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/PulseNexus/SysPulse-Releases/releases/download/v1.0.0-beta.4/SysPulse-Setup-1.0.0-beta.4.exe)

[![Portable Edition](https://img.shields.io/badge/Portable_Edition-705AB5?style=for-the-badge)](https://github.com/PulseNexus/SysPulse-Releases/releases/download/v1.0.0-beta.4/SysPulse-portable-1.0.0-beta.4.zip)
[![Advanced Sensors](https://img.shields.io/badge/Advanced_Sensors-30363D?style=for-the-badge)](https://github.com/PulseNexus/SysPulse-Releases/releases/download/v1.0.0-beta.3/SysPulse-Advanced-Sensor-Helper-1.0.0-beta.3.zip)

![Version](https://img.shields.io/badge/Version-1.0.0--beta.4-A69BE0)
![Platform](https://img.shields.io/badge/Platform-Windows_10%2F11-blue)
![License](https://img.shields.io/badge/License-Freeware-green)

[All Releases](https://github.com/PulseNexus/SysPulse-Releases/releases) · [Report a Bug](https://github.com/PulseNexus/SysPulse-Releases/issues) · [Sensor Installation Guide](ADVANCED-SENSORS.md)

</div>

---

## About SysPulse

**SysPulse** brings your computer's hardware, performance, and system health into one clean interface.

Monitor your components in real time, explore historical performance, investigate system problems, and manage essential Windows functions without jumping between multiple applications.

Designed to offer detailed information without unnecessary complexity.

## Features

### Real-Time Hardware Monitoring

- CPU utilization, frequency, temperature, and available power readings.
- GPU utilization, temperature, memory, and available sensor readings.
- RAM and swap usage.
- Storage performance and health information.
- Network traffic and activity.
- Hardware discovery and sensor availability information.

Advanced hardware measurements depend on supported components and optional sensor integrations.

### Easy & Advanced Modes

**Easy Mode** provides a simplified overview of your PC.

**Advanced Mode** provides additional metrics, management controls, and detailed system information.

### Customizable Dashboards

- Personalized dashboard layouts.
- Independent layouts for Easy and Advanced modes.
- Live hardware widgets.
- Saved dashboard preferences.

### Historical Monitoring

- Record system performance over time.
- Examine historical charts and measurements.
- Select metrics and time ranges.
- Export monitoring data.
- Configure history retention.

### Incident Recorder — New in Beta 4

SysPulse includes a local diagnostic recorder that helps explain what happened before and after significant system events.

- Automatically detects supported critical hardware and performance conditions.
- Preserves up to five minutes of pre-incident history.
- Captures up to two minutes of recovery data when available.
- Correlates interruptions with available Windows event information.
- Supports manual diagnostic snapshots.
- Displays incident timelines and charts.
- Exports readable reports, JSON, and CSV.
- Offers privacy-conscious export options.
- Provides configurable retention and storage limits.

**Incident Recorder is enabled by default** and operates locally. Reports are never uploaded automatically.

### Alerts & Diagnostics

- Custom monitoring rules and thresholds.
- Alert severity and cooldown controls.
- Hardware diagnostics and health reports.
- Persistent alert configurations.
- Optional desktop notifications.

### Windows System Management

- Process management.
- Windows service management.
- Startup application management.
- Power plan controls.
- Supported system power actions.

Some actions require administrator authorization.

### Remote Monitoring

Access supported read-only system monitoring information from another device using the optional remote monitoring functionality.

Remote access must be configured by the user.

### Appearance

- Dark Mode.
- Light Mode.
- System theme.
- Modern Minimalism interface.
- Lavender-accented visual design.

---

## Downloads

| Edition | Description |
| --- | --- |
| [Windows Installer](https://github.com/PulseNexus/SysPulse-Releases/releases/download/v1.0.0-beta.4/SysPulse-Setup-1.0.0-beta.4.exe) | Recommended for most users |
| [Portable Edition](https://github.com/PulseNexus/SysPulse-Releases/releases/download/v1.0.0-beta.4/SysPulse-portable-1.0.0-beta.4.zip) | Run SysPulse without installing |
| [Advanced Sensor Helper (Beta 3)](https://github.com/PulseNexus/SysPulse-Releases/releases/download/v1.0.0-beta.3/SysPulse-Advanced-Sensor-Helper-1.0.0-beta.3.zip) | Optional advanced hardware monitoring component; not rebuilt or retested for Beta 4 |

For optional advanced sensors, read the [installation guide](ADVANCED-SENSORS.md).

## System Requirements

- Windows 10 or Windows 11.
- 64-bit Windows installation.
- WebView2 runtime where required.
- Administrator authorization for certain management actions and optional sensors.

## What's New in Beta 4?

- **Fixed:** Deleted default alert rules no longer regenerate.
- **New:** Automatic Incident Recorder.
- **New:** Incident history, diagnostic snapshots, and exports.
- **Improved:** Windows event correlation and incident classification.
- **Improved:** Custom confirmation dialogs replace browser popups.
- **Improved:** Historical Monitoring and Insights reliability.

[View Beta 4 Release](https://github.com/PulseNexus/SysPulse-Releases/releases/tag/v1.0.0-beta.4)

## Known Limitations

SysPulse is currently in public beta.

- Some hardware configurations have not been physically tested.
- Advanced sensors depend on compatible hardware and additional components.
- The installer is unsigned and may trigger Microsoft Defender SmartScreen.
- Incident recovery depends on previously saved measurements and available Windows events.
- New measurements cannot be collected while Windows is frozen or powered off.
- Extended performance and reliability testing remains ongoing.

## Feedback & Bug Reports

Found a bug, incorrect sensor reading, crash, or interface issue?

[**Report a Bug**](https://github.com/PulseNexus/SysPulse-Releases/issues/new)

When reporting an issue, include your Windows version, SysPulse version, and relevant details.

Incident Recorder reports can help with troubleshooting. Review exported diagnostics before sharing them publicly.

## Licensing

SysPulse is **proprietary freeware**.

The application is free to use under the terms of its [LICENSE](LICENSE).

Third-party components remain subject to their respective licenses.

Source code is not publicly distributed.

---

<div align="center">

**SysPulse** — Your system. Every detail.

Published by **Pulse**.

Created and owned by **Mest**.

Copyright © 2026 Mest. All rights reserved.

</div>

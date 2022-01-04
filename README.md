# REV Hardware Client Overview

The REV Hardware Client is software designed to make managing REV devices easier for the user. This Client automatically detects connected device(s), downloads the latest software for those device(s), and allows for seamless updating of the device(s).&#x20;

|                                                                          REV Hardware Client - Version 1.4.0                                                                         |
| :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| [![](.gitbook/assets/download-latest-rev-hardware-client.svg)](https://github.com/REVrobotics/REV-Software-Binaries/releases/download/rhc-1.4.0/REV-Hardware-Client-Setup-1.4.0.exe) |

### Feature Summary

* Automatically detect supported devices when connected via USB
* Connect a REV Control Hub via Wi-Fi
* One Click update of all software on connected devices
* Pre-download software updates without a connected device
* Back up and restore user data from supported devices (Control Hub and SPARK MAX)
* Install and switch between DS and RC applications on Android Devices
* Access the Robot Control Console on the Control Hub
* Auto-update to latest version of the REV Hardware Client
* Display devices connected via RS485

### Supported Devices

* REV Control Hub (REV-31-1595)
* REV Expansion Hub (REV-31-1153)
* REV Driver Hub (REV-31-1596)
* Android Device via ADB
* REV SPARK MAX (REV-11-2158)
* Generic CAN Devices

### Change Log

#### Version 1.3.0

* General updates:
  * Adds FTC log viewer utility
    * Can load log files directly from supported devices, or from anywhere on the user's computer
    * Allows users to easily filter, search, and sort events parsed from log files
    * Graphs the occurrence of important robot issues, and their corresponding timestamps
    * Supports match, robot controller, driver station, Wi-Fi, and updater logs
  * Shows release notes for client even when an update is not available
  * Scales telemetry graph ranges automatically when using default ranges
  * Fixes issue with devices showing up multiple times when changing CAN IDs
  * Shows update progress for all devices that are updating simultaneously
  * Updates users to the latest available client version when removing a software channel
  * Other minor bug fixes
* Control Hub specific updates:
  * Improves stability of the connection to a Control Hub
  * Includes program and manage logs with Control Hub diagnostic data sent to REV
* SPARK MAX specific updates:
  * Fixes issue with SPARK MAX analog telemetry
  * Improves SPARK MAX parameter fields
  * Fixes issue where a SPARK MAX in recovery mode could not be updated on some computers
  * Adds interface to run multiple SPARK MAX devices
  * Adds simplified support for configuring follower mode (currently limited to following another SPARK MAX)
  * Shows a dropdown for the `Alternate Encoder -> kDataPortConfig` parameter

#### Version 1.2.0

* General updates:
  * Allow installing previous versions of software
  * Show client updates are available more subtly&#x20;
  * Reconnect to ADB if it resets&#x20;
  * Show manufacturer names for generic android devices
  * Fixes issues with Control Hub and Expansion Hub firmware falsely saying out of date
  * Other minor bug fixes
* Control Hub specific updates:
  * Shows warning when the Control Hub internal communication is not responding
  * Shows warning when Control Hub webserver is not running
  * Full screen mode for Program and Manage Tab
  * Prompts to backup Control Hub data if backup on file is over a week old
  * Confirmation now required to restore backed up files
  * Fix issues with not all files being restored
* SPARK MAX specific updates:
  * Fixed bug where Alternate Encoder telemetry data was displaying incorrectly
  * Allow for complete Factory Reset of all parameters on SPARK MAX
  * Disabled setting of parameters that have no effect in current configuration
  * Fixed bug where the Client would turn white on selecting SPARK MAX

#### Version 1.1.0

* Adds support for SPARK MAX and other CAN devices&#x20;
* Allows for updating SPARK MAX devices, installing APIs, running motors, and viewing data from the SPARK MAX and its motor.&#x20;
* Shows all recognized devices on a CAN bus, and the data that is sent on the bus

#### Version 1.0.0

* Original Release


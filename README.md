# HP_Probook4530s_DSDT_Fan

Here is my effort to make (parts of) Probook 4530s laptop's DSDT table [ACPI 4.0][acpi] compliant.

For now, I'll be focusing on thermal management. Hopefully, I'll be able to expose cooling fan to thermal sysfs interface, so that it could be used with [thermald][td].

[td]: https://github.com/01org/thermal_daemon "Linux Thermal Daemon"
[acpi]: http://www.acpi.info/spec.htm "ACPI Specification"
[mac]: https://github.com/RehabMan/HP-ProBook-4x30s-DSDT-Patch "Probook 4530s DSDT patches for Hackintosh"

*THIS IS WORK IN PROGRESS AND MAY DAMAGE YOUR COMPUTER! USE AT YOUR OWN RISK.*
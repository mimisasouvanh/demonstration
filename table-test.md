<a name="_Ref421024367"></a><a name="_Ref421024381">Table</a> 3: CHID Definitions

| HardwareID-0 | Manufacturer + Family + Product Name + SKU Number + BIOS Vendor + BIOS Version + BIOS Major Release + BIOS Minor Release |
| --- | --- |
| HardwareID-1 | Manufacturer + Family + Product Name + BIOS Vendor + BIOS Version + BIOS Major Release + BIOS Minor Release |
| HardwareID-2 | Manufacturer + Product Name + BIOS Vendor + BIOS Version + BIOS Major Release + BIOS Minor Release |
| HardwareID-3 | Manufacturer + Family + ProductName + SKU Number + Baseboard_Manufacturer + Baseboard_Product |
| HardwareID-4 | Manufacturer + Family + ProductName + SKU Number |
| HardwareID-5 | Manufacturer + Family + ProductName |
| HardwareID-6 | Manufacturer + SKU Number + Baseboard_Manufacturer + Baseboard_Product |
| HardwareID-7 | Manufacturer + SKU Number |
| HardwareID-8 | Manufacturer + ProductName + Baseboard_Manufacturer + Baseboard_Product |
| HardwareID-9 | Manufacturer + ProductName |
| HardwareID-10 | Manufacturer + Family + Baseboard_Manufacturer + Baseboard_Product |
| HardwareID-11 | Manufacturer + Family |
| HardwareID-12 | Manufacturer + Enclosure Type |
| HardwareID-13 | Manufacturer + Baseboard_Manufacturer + Baseboard_Product |
| HardwareID-14 | Manufacturer |

OEMs will need to provide the correct CHID information to the driver publisher. The ComputerHardwareIds.exe tool ([http://msdn.microsoft.com/en-us/library/windows/hardware/ff543505(v=vs.85).aspx](http://msdn.microsoft.com/en-us/library/windows/hardware/ff543505(v=vs.85).aspx)), included in the Windows Desktop Tools SDK, can help facilitate reporting CHIDs from a known set of System Management BIOS (SMBIOS) values.

Note that the ComputerHardwareIds.exe tool performs two different tasks:

1)      **Default Behavior:** The tool reports the current system settings.
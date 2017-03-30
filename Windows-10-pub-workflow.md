<div style="border-width: 1pt medium medium; border-style: solid none none; border-color: rgb(0, 188, 242) currentColor currentColor; padding: 1pt 0in 0in; border-image: none;">

Windows 10 Driver Publishing Workflow

</div>

June 2015

Some information relates to pre-released product, which may be substantially modified before it's commercially released. Microsoft makes no warranties, express or implied, with respect to the information provided here.

Copyright

This document is provided "as-is." Information and views expressed in this document, including URL and other Internet Web site references, may change without notice.

Some examples depicted herein are provided for illustration only and are fictitious. No real association or connection is intended or should be inferred.

This document does not provide you with any legal rights to any intellectual property in any Microsoft product. You may copy and use this document for your internal, reference purposes.

© 2015 Microsoft. All rights reserved.

Please refer to Microsoft Trademarks for a list of trademarked products.

Bluetooth® is a trademark owned by Bluetooth SIG, Inc., USA and licensed to Microsoft Corporation.

All other trademarks are property of their respective owners.

Contents

[1\. Driver Publishing Workflow for Windows 10\. 5](#_Toc423444273)

[2\. Windows Update Distribution. 5](#_Toc423444274)

[2.1       Pre-Windows 10 Driver Update Scenarios. 5](#_Toc423444275)

[2.2       Reselling (Redistributing) Drivers and the Driver Update Acceptable Process. 6](#_Toc423444276)

[2.3       Pre-Windows 10 Driver Publishing Workflow.. 6](#_Toc423444277)

[2.3.1       Driver Submission Options. 6](#_Toc423444278)

[2.3.2       Removing a Driver from Windows Update. 8](#_Toc423444279)

[2.4       Windows 10 Initial Driver Publishing Workflow (29 April 2015). 8](#_Toc423444280)

[2.4.1       Driver Submission Options. 8](#_Toc423444281)

[2.5       Windows 10 Release Driver Publishing Workflow.. 9](#_Toc423444282)

[2.5.1       New Features. 9](#_Toc423444283)

[2.5.2       Driver Publishing Workflow.. 10](#_Toc423444284)

[3\. Driver Targeting. 11](#_Toc423444285)

[3.1       Background. 11](#_Toc423444286)

[3.2       Computer Hardware IDs. 11](#_Toc423444287)

[3.2.1       Tips for consistent CHIDs. 13](#_Toc423444288)

[3.3       Types of Targeting. 13](#_Toc423444289)

[3.3.1       Installation Targeting. 14](#_Toc423444290)

[3.4       CHIDs: Installation Targeting vs. Distribution Targeting. 15](#_Toc423444291)

[3.5       Scenarios. 16](#_Toc423444292)

[3.5.1       Publishing Drivers with Distribution Targeting. 16](#_Toc423444293)

[3.5.2       Publishing Drivers with Installation Targeting. 17](#_Toc423444294)

[3.5.3       Reselling a submission and using Distribution Targeting. 17](#_Toc423444295)

[3.5.4       Reselling a submission and using Installation Targeting with driver submissions. 18](#_Toc423444296)

[3.6       Examples. 19](#_Toc423444297)

[4\. Publication restrictions. 26](#_Toc423444298)

[5\. Firmware Update support for systems. 28](#_Toc423444299)

[5.1       UEFI Firmware UpdateCapsule Support. 28](#_Toc423444300)

[5.1.1       Publishing an UpdateCapsule: 29](#_Toc423444301)

[5.1.2       Validating Firmware Update Capsules. 29](#_Toc423444302)

[6\. Driver publishing FAQ.. 30](#_Toc423444303)

[7\. Document Revision History. 31](#_Toc423444304)

[5.2       November 2014 – Initial Release. 31](#_Toc423444305)

[5.3       January 2015 Update. 31](#_Toc423444306)

[5.4       April 2015 Update. 32](#_Toc423444307)

[5.5       May - June 2015 Upadate. 32](#_Toc423444308)
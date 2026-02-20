# Linux Foundation ONMI Project Transport API (TAPI) Documentation

**This is the documentation for release version ***2.5.2*** of the Linux Foundation ONMI Project Transport API (TAPI) SDK
The SDK is being released under the Apache 2.0 license.**

The [LF TAPI](https://github.com/Open-Network-Models-and-Interfaces-ONMI/TAPI-Home) project is [chartered ](https://github.com/Open-Network-Models-and-Interfaces-ONMI/onmi-home/blob/main/ONMI-charter) under the LF Projects. [OMNI ](https://github.com/Open-Network-Models-and-Interfaces-ONMI/onmi-home/wiki) TAPI is responsible for the development of this SDK as an Open Source project. 

This [release](https://github.com/Open-Network-Models-and-Interfaces-ONMI/TAPI/tree/v2.5.2) includes technology-agnostic interfaces to the following functional modules:
- Topology Service
- Connectivity Service
- Path Computation Service
- OAM Service
- Fault Management Service
- Equipment Inventory Service
- Virtual Network Service
- Notification Service
- Streaming Service
- gNMI Streaming Service

It also includes support for the following technology-specific interface profiles:
- Photonic Media (L0-WDM)
- Optical Transport Network (L1-OTN)
- Carrier Ethernet (L2)

This release includes all the documentation associated to version [2.5.2 of the TAPI SDK](https://github.com/Open-Network-Models-and-Interfaces-ONMI/TAPI/releases/tag/v2.5.2):

- [**_TAPI Reference Implementation Agreement (RIA TR-547 3.1.1)_**](https://github.com/Open-Network-Models-and-Interfaces-ONMI/TAPI-Documentation/blob/v2.5.2/ReferenceImplementationAgreements/TR-547)
  - This LF Technical Recommendation (TR) provides a set of ***guidelines and recommendations*** for a standard use of the TAPI models in combination with the RESTCONF protocol for the implementation of the interface between network systems in charge of the control/management of networks based on WDM/OTN technologies.
- [**_TAPI Reference Implementation Agreement for Streaming (RIA TR-548 3.1.1)_**](https://github.com/Open-Network-Models-and-Interfaces-ONMI/TAPI-Documentation/blob/v2.5.2/ReferenceImplementationAgreements/TR-548)
  - This document is a supplement to the TR-547, to explain TAPI streaming and provide a set of ***guidelines and recommendations*** for use of TAPI streaming.
 
The Reference Implementation Agreements are supported by two associated documents:
- [**_TAPI_Alarm_TCA_List_v3.0.0_**](https://github.com/Open-Network-Models-and-Interfaces-ONMI/TAPI-Documentation/blob/v2.5.2/AlarmsAndNotifications) 
- [**_TAPI Notification and Streaming Sequences_**](https://github.com/Open-Network-Models-and-Interfaces-ONMI/TAPI-Documentation/blob/v2.5.2/AlarmsAndNotifications)

Guideline for the generation of YANG/TREE/OAS modules from UML model:
- [**_UML2Yang2Oas Tool User Guide_**](https://github.com/Open-Network-Models-and-Interfaces-ONMI/TAPI-Documentation/blob/v2.5.2/ToolingGuidelines) 

As the most deployed release of TAPI at this point is TAPI 2.1.3 (TIP recommended) a detailed differences between 2.1.3 and 2.5.2 can be obtained using
- https://github.com/Open-Network-Models-and-Interfaces-ONMI/TAPI/compare/v2.1.3...v2.5.2

As TAPI 2.5.x is also a TIP recommended release a detailed differences between 2.5.0 and 2.5.2 can be obtained using
- https://github.com/Open-Network-Models-and-Interfaces-ONMI/TAPI/compare/v2.5.0...v2.5.2

[**_HighLevelDiff_Tapi2.1.3To2.5.2.pdf_**](https://github.com/Open-Network-Models-and-Interfaces-ONMI/TAPI-Documentation/blob/v2.5.2/DeltaDocument/HighLevelDiff_Tapi2.1.3To2.5.2.pdf)  highlights the key changes from 2.1.3 to 2.5.2

**Summary of changes**
- Correction to remove "cofig false" YANG issue
- Addition of paginated get (experimental)
- String field restrictions relaxed to “any conformant YANG string” throughout. Explanation added in TR-547 section 2.8 String fields.
- Various minor improvements to documentation

## What's Changed
* TR updates for TAPI 2.5.2 by @nigel-r-davis in https://github.com/Open-Network-Models-and-Interfaces-ONMI/TAPI-Documentation/pull/4


**Full Changelog**: https://github.com/Open-Network-Models-and-Interfaces-ONMI/TAPI-Documentation/compare/v2.5.0...v2.5.2
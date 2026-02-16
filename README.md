# Linux Foundation ONMI Project Transport API (TAPI) Documentation

**This is the documentation for release version ***2.1.5*** of the Linux Foundation ONMI Project Transport API (TAPI) SDK
The SDK is being released under the Apache 2.0 license.**

The [LF TAPI](https://github.com/Open-Network-Models-and-Interfaces-ONMI/TAPI-Home) project is [chartered ](https://github.com/Open-Network-Models-and-Interfaces-ONMI/onmi-home/blob/main/ONMI-charter) under the LF Projects. [OMNI ](https://github.com/Open-Network-Models-and-Interfaces-ONMI/onmi-home/wiki) TAPI is responsible for the development of this SDK as an Open Source project. 

This [release](https://github.com/Open-Network-Models-and-Interfaces-ONMI/TAPI/tree/v2.1.5) includes technology-agnostic interfaces to the following functional modules:
- Topology Service
- Connectivity Service
- OAM Service
- Path Computation Service
- Virtual Network Service
- Notification Service
- Equipment Inventory Service
- Streaming Service
- Physical Route (new)

It also includes support for the following technology-specific interface profiles
- Carrier Ethernet (L2)
- Optical Transport Network (L1-ODU)
- Photonic Media (L0-WDM)

This release includes all the documentation associated to version [2.1.5 of the TAPI SDK](https://github.com/Open-Network-Models-and-Interfaces-ONMI/TAPI/releases/tag/v2.1.5):

- [**_TAPI Reference Implementation Agreement (RIA TR-547 1.2)_**](https://github.com/Open-Network-Models-and-Interfaces-ONMI/TAPI-Documentation/blob/v2.1.5/ReferenceImplementationAgreements/TR-547)
  - This LF Technical Recommendation (TR) provides a set of ***guidelines and recommendations*** for a standard use of the TAPI models in combination with the RESTCONF protocol for the implementation of the interface between network systems in charge of the control/management of networks based on WDM/OTN technologies.
- [**_TAPI Reference Implementation Agreement for Streaming (RIA TR-548 1.2)_**](https://github.com/Open-Network-Models-and-Interfaces-ONMI/TAPI-Documentation/blob/v2.1.5/ReferenceImplementationAgreements/TR-548)
  - This document is a supplement to the TR-547, to explain TAPI streaming and provide a set of ***guidelines and recommendations*** for use of TAPI streaming.
 
The Reference Implementation Agreements are supported by two associated documents:
- [**_TAPI_Alarm_TCA_List_v1.0.0_**](https://github.com/Open-Network-Models-and-Interfaces-ONMI/TAPI-Documentation/blob/v2.1.5/AlarmsAndNotifications) 

As the most deployed release of TAPI at this point is TAPI 2.1.3 (TIP recommended) a detailed differences between 2.1.3 and 2.1.5 can be obtained using
- https://github.com/Open-Network-Models-and-Interfaces-ONMI/TAPI/compare/v2.1.3...v2.1.5

As TAPI 2.5.x is also a TIP recommended release a detailed differences between 2.1.5 and 2.5.2 can be obtained using
- https://github.com/Open-Network-Models-and-Interfaces-ONMI/TAPI/compare/v2.1.5...v2.5.2

[**_HighLevelDiff_Tapi2.1.3To2.1.5.pdf_**](https://github.com/Open-Network-Models-and-Interfaces-ONMI/TAPI-Documentation/tree/v2.1.5/DeltaDocument)  highlights the key changes from 2.1.3 to 2.1.5

## What's Changed
* Tapi 2.1.3 fixes by @nigel-r-davis in https://github.com/Open-Network-Models-and-Interfaces-ONMI/TAPI-Documentation/pull/2
* TR updates for TAPI 2.1.5 by @nigel-r-davis in https://github.com/Open-Network-Models-and-Interfaces-ONMI/TAPI-Documentation/pull/3

**Summary of changes**
- Addition of physical route
- Addition of paginated get (experimental)
- String field restrictions relaxed to “any conformant YANG string” throughout. Explanation added in TR-547 section 2.8 String fields.
- transmited-power, received-power, otsi-termination, selected-application-identifier and otsi-config made Conditional. 
- Various minor improvements to documentation
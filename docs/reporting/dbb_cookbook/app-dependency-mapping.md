---
title: "Application Dependency Mapping"
sidebar_position: 1
---

**Application Dependency Mapping Data Building Blocks**

- [Business App Dependencies](reporting/dbb_cookbook/business-app-dependencies.md)
- [Business App Device Impacts](reporting/dbb_cookbook/business-app-device-impacts.md)
- [Business App Hardware EOL / EOS Impact](reporting/dbb_cookbook/business-app-hardware-eol-eos-impact.md)
- [Business App Operating System EOL / EOS](reporting/dbb_cookbook/business-app-operating-system-eol-eos.md)
- [Workload and Application Communication - Business App Communications](reporting/dbb_cookbook/workload-and-application-communication-business-app-communications.md)
- [Workload and Application Communication - IP Service Communications](reporting/dbb_cookbook/workload-and-application-communication-ip-service-communications.md)

Data Building Blocks are materialized database views composed with customer-specific use cases in mind to allow users to quickly create reports with little-to-no extra view joining required. These views are refreshed on a nightly basis. Because of the requirements for this type of reporting, it is necessary for the user to have access to all the Device42 data. A special privilege has been created called _Data Building Blocks_ for this purpose and must be granted for a user to have access to the DBB views. The reason for this is to simplify the access to data for reporting and insight needs.

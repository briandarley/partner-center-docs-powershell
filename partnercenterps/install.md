---
services: parnter-center
documentationcenter: ''

ms.service: partner-center
ms.workload: 
ms.tgt_pltfrm: na
ms.devlang: powershell
ms.topic: article
ms.date: 10/22/2018
ms.author: iswillia
ms.custom:
ms.reviewer:
---

# Partner Center PowerShell module

## Installing the Module

Run the following command in an elevated PowerShell session to install the Partner Center module:

```powershell
Install-Module -Name PartnerCenter
```

If you have an earlier version of the Partner Center PowerShell modules installed from the PowerShell Gallery and would like to update to the latest version, run the following commands from an elevated PowerShell session.

**Note:** `Update-Module` installs the new version, however, it does not remove the old version.

```powershell
# Install the latest version of the Partner Center PowerShell module
Update-Module -Name PartnerCenter
```
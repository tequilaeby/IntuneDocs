---
title: Windows PC management capabilities in Microsoft Intune
ms.custom: na
ms.reviewer: na
ms.service: microsoft-intune
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 77fa5c66-a87c-47df-964c-800eea509b33
author: robstackmsft
---
# Windows PC management capabilities (with the Microsoft Intune computer client)
In most scenarios, you will [enroll your Windows device with Intune](http://docsmsftstage.azurewebsites.net/Intune/Topic/Set-up-Windows-device-management-with-Microsoft-Intune.html "enroll your Windows device with Intune") which provides a greater set of capabilities than the computer client. However, you can also manage PCs by using the Intune computer client which provides the following features:

-   **Manage software updates** - You can keep PCs up-to-date, and manage when updates are applied.

-   **Windows Firewall policy** - This helps to ensure that no PC used by your company has an inactive or improperly-configured Windows Firewall.

-   **Anti-malware protection** - [!INCLUDE[wit_nextref](/includes/wit_nextref_md.md)] includes Endpoint Protection, which helps protect your PCs from malware.

-   **Remote assistance** - [!INCLUDE[wit_nextref](/includes/wit_nextref_md.md)] allows users to contact IT support staff, who can then provide assistance using a remote desktop feature that is included with [!INCLUDE[wit_nextref](/includes/wit_nextref_md.md)].

-   **Software license management** - Track how many software licenses are available, and how many available licenses are being used.
-   **App deployment** - Deploy software to PCs that you manage. Some app management features are not available when you manage PCs with the client software.
## When to use the computer client
Consider using the Intune computer client when you want to:
<ul>
<li>Use any of the capabilities above to manage your Windows PCs.</li>
<li>Manage a Windows PC that runs an operating system that is not supported for enrollment</li>




</ol>

## <a name="BKMK_ClientReqs"></a>Requirements for PC management
###**Operating systems**
[!INCLUDE[wit_nextref](/includes/wit_nextref_md.md)] can manage PCs running the following Windows versions (both x86 and x64) with mobile device management:


-   **Windows Vista** - Business, Enterprise and Ultimate versions.

-   **Windows 7** - Professional, Enterprise, and Ultimate versions (with no service pack, or with SP1).

-   **Windows 8** - Professional and Enterprise versions.

-   **Windows 8.1** - Professional and Enterprise versions.

-   **Windows 10** - Professional, Enterprise and Education versions.

###**Minimum hardware requirements for the Intune computer client**:
The following are minimum hardware requirements for installing the [!INCLUDE[wit_nextref](/includes/wit_nextref_md.md)] client:

|Requirement|More information|
|---------------|--------------------|
|Network|The client requires the PC to have Internet connectivity.|
|Processor and Memory|Refer to the processor and RAM requirements for the PC's operating system.|
|Disk space|200 MB available disk space before the client software is installed.|
###**Further requirements**: 
The following are software requirements for installing the [!INCLUDE[wit_nextref](/includes/wit_nextref_md.md)] client:

|Requirement|More information|
|---------------|--------------------|
|Administrative permissions|The account that installs the client software must have local administrator permissions to that PC.|
|Windows Installer 3.1|The PC must have, at a minimum, Windows Installer 3.1 installed.|
|Remove incompatible client software|Before you install the [!INCLUDE[wit_nextref](/includes/wit_nextref_md.md)] client software, you must uninstall the following client software from that PC:<br /><br />-   Any version of [!INCLUDE[cm5short](/includes/cm5short_md.md)]<br />-   Any version of [!INCLUDE[sccmshortname](/includes/sccmshortname_md.md)]<br />-   Any version of Microsoft Systems Management Server (SMS)|

##Next steps

Now you've discovered some of the capabilities you can use with the Intune client software, you'll need to learn about how to use this to [manage your PCs](manage-windows-pcs-with-microsoft-intune.md). Once they are managed, you can take advantage of all of the capabilities you've read about in this topic.  


### See Also

[Manage Windows PCs with Microsoft Intune](manage-windows-pcs-with-microsoft-intune.md)

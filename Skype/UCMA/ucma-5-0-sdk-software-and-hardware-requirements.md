---
title: UCMA 5.0 SDK software and hardware requirements
TOCTitle: Software and hardware requirements
ms:assetid: 521f7820-f6ed-4706-905d-9802674ab029
ms:mtpsurl: https://msdn.microsoft.com/library/Dn465960(v=office.16)
ms:contentKeyID: 65239773
ms.date: 07/27/2015
mtps_version: v=office.16
---

# UCMA 5.0 SDK software and hardware requirements

**Applies to**: Skype for Business 2015

This topic describes the software and hardware requirements for Microsoft Unified Communications Managed API 5.0 SDK.

## Software requirements

The following are the software requirements for a successful installation of UCMA 5.0 SDK.

- Supported operating systems:
    
  - Microsoft Windows Server 2012 R2
  - Microsoft Windows Server 2012  
  - Microsoft Windows Server 2008 R2 SP1 or higher service pack, 64-bit version 
  - Microsoft Windows 7 SP1 or higher service pack, 64-bit (see following note)
    
  > [!IMPORTANT]
  > - UCMA 5.0 SDK is available only in a 64-bit version.
  > - Windows XP and Windows Server 2008 are not supported.
  > - Development is supported only in 64-bit environments.
  > - The Desktop Experience feature must be enabled on Windows Server 2008 R2 SP1. For more information, see [Desktop Experience Overview](/previous-versions/windows/it-pro/windows-server-2008-R2-and-2008/cc772567(v=ws.11)).
  > - Media Foundation is required on Windows Server 2012.

- Microsoft Windows PowerShell 3.0 RTM
    
  > [!IMPORTANT]
  > To install PowerShell 3.0, see [Windows Management Framework 3.0](https://www.microsoft.com/download/details.aspx?id=34595).

- Microsoft .NET Framework 4.5

> [!NOTE]
> - Side-by-side installations of UCMA 4.0 SDK and UCMA 5.0 SDK are not supported.
> - When Windows Media format is installed or enabled, the computer must be restarted.
> - Windows Media Format must be present if you use UCMA 5.0 to develop applications that play or record media.
> - UcmaSdkSetup.exe must be run with elevated privileges.

## Hardware requirements

The following are the hardware requirements for successful installation of UCMA 5.0 SDK:

- Typical current hardware configurations with a minimum of 2 GB of RAM are recommended for the supported operating systems.

## See also

- [Microsoft.Rtc.Collaboration Namespace](/dotnet/api/microsoft.rtc.collaboration?view=ucma-api-5.0)
- [Microsoft.Rtc.Collaboration.AudioVideo.VoiceXml Namespace](/dotnet/api/Microsoft.Rtc.Collaboration.AudioVideo.VoiceXml?view=ucma-voice)
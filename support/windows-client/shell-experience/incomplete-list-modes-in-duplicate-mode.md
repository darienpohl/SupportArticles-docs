---
title: List All Modes displays incomplete list of modes 
description: Provides a solution to an issue where the list of available modes is different than the list displayed in Windows 7 when you use multiple displays in duplicate mode in Windows 8.
ms.date: 09/14/2020
author: Deland-Han
ms.author: delhan
manager: dscontentpm
audience: itpro
ms.topic: troubleshooting
ms.prod: windows-client
localization_priority: medium
ms.reviewer: kaushika, kimnich
ms.prod-support-area-path: DPI and Display Issues
ms.technology: ShellExperience
---
# Windows 8: "List All Modes" in Advanced Display Settings Control Panel displays incomplete list of modes when in "Duplicate" mode

This article provides a solution to an issue where the list of available modes is different than the list displayed in Windows 7
when you use multiple displays in "duplicate" mode in Windows 8.

_Original product version:_ &nbsp; Windows 8  
_Original KB number:_ &nbsp; 2813712

## Symptoms

Consider the following scenario:

The operating system is Windows 8 and you are using multiple displays in "duplicate" mode. When selecting Advanced Settings in the Screen Resolution Control Panel and then selecting the List All Modes button on the Adapter tab of the monitor and display driver dialog box, the list of available modes is different than the list that is displayed in Windows 7.

## Cause

This behavior is by design. The list of display modes available when "duplicate" mode is selected on a Windows 8 client is based upon the selected primary monitor at the time of selecting "duplicate" mode. In Windows 7, all display modes are displayed regardless of the primary monitor selection.

## Resolution

If the desired display mode is not available in "duplicate" mode, select a different monitor as the primary monitor prior to selecting "duplicate" display mode.
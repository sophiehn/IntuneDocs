---
# required metadata

title: Remotely lock managed devices with Intune
titlesuffix: "Azure portal"
description: Learn how to use Intune to remotely lock devices you manage."
keywords:
author: arob98
ms.author: angrobe
manager: angrobe
ms.date: 01/22/2018
ms.topic: article
ms.prod:
ms.service: microsoft-intune
ms.technology:
ms.assetid: 3b67f285-229d-4a0f-ae34-0402a20b4518

# optional metadata

#ROBOTS:
#audience:
#ms.devlang:
#ms.reviewer: ilwu
ms.suite: ems
#ms.tgt_pltfrm:
ms.custom: intune-azure

---

# Remotely lock managed devices with Intune


[!INCLUDE[azure_portal](./includes/azure_portal.md)]

The **Remote lock** device locks the selected device. The device owner must use their passcode to unlock it. You can only remotely lock a device that has a PIN or password set.

## Supported platforms

Remote lock is supported for the following platforms:

|Platform|Support status|
|---|---|
|Android|Yes|
|iOS|Yes|
|macOS|Yes|
|Windows 10|Yes|
|Windows 10 Mobile|Yes|
|Windows Phone|Yes, for Windows Phone 8.1 and later|

> [!NOTE]  
> For macOS devices, you set a 6-digit recovery PIN. When locked, the **Device overview** blade displays the PIN until another device action is sent.

## How to remote lock a device

1. Sign into the Azure portal.
2. Choose **More Services** > **Monitoring + Management** > **Intune**.
3. On the **Intune** blade, choose **Devices**.
4. On the **Devices and groups** blade, choose **All devices**.
5. From the list of devices you manage, choose a device, and then choose the **Remote lock** device remote action.

## Next steps

To see the status of the action you just took, on the **Devices and groups** blade, choose **Device Actions**.

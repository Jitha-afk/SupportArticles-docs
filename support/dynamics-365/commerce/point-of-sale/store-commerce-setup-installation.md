---
title: Troubleshoot Store Commerce setup and installation issues 
description: Explains how to solve the setup and installation issues in the Microsoft Dynamics 365 Commerce Store Commerce app.
author: josaw1 
ms.author: josaw
ms.reviewer: brstor
ms.date: 09/01/2023
---
# Troubleshoot issues with Store Commerce setup and installation 

This article explains how to troubleshoot setup and installation issues in the Microsoft Dynamics 365 Commerce Store Commerce app.

## Issue 1: I can't activate the app, and I receive a connectivity error message

After you enter the valid Cloud POS URL, you might receive a connectivity error message like the following one:

> A connectivity error has occurred, and your device can't connect to Cloud POS. The Cloud POS URL typed may have some issues.

In this case, review the URL for typographical errors, or determine whether Cloud POS can't be reached because it's offline.

Additionally, verify that the Cloud Scale Unit (CSU) version is 10.0.25 (9.35.\*.\*) or later. CSU version 10.0.25 or later is required to use the Store Commerce app.

## Issue 2: I can't activate the app because of an invalid URL or an error state

If the Cloud POS URL that you entered isn't valid and you want to change it, or if the Store Commerce app is in an error state during activation, you can restart the process by resetting the app. The Store Commerce app will save only a valid Cloud POS URL.

To reset the Store Commerce app, follow these steps:

1. On the Windows **Start** menu, select and hold (or right-click) the app, and then select **More** > **App settings**.
2. Scroll down the app settings page until you find the **Reset** button.
3. Select **Reset**. Then, when you're prompted, confirm that you want to reset the app.

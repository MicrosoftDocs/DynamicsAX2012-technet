---
title: Debug code in a Retail online sample store
TOCTitle: Debug code in a Retail online sample store
ms:assetid: 3bc6eddc-6e74-46b6-bbe2-46318feb619b
ms:mtpsurl: https://technet.microsoft.com/library/Dn720293(v=AX.60)
ms:contentKeyID: 62221433
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Debug code in a Retail online sample store 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

The sample online stores for Retail in Microsoft Dynamics AX 2012 R3 use SharePoint 2013 and code that is found in the Retail SDK. You can debug the sample online store code for the SharePoint pages in a browser window or by using Visual Studio. You use the F12 developer tools to debug code in a browser window. In Visual Studio, you can attach the worker process to debug your code.

## Preparation for debugging

You must recompile the source code found in the Retail SDK and redeploy it before you can debug the code for the sample Retail online stores.

## Debugging Retail online store site pages

The Retail SDK contains source code for the sample online stores. For more information, see [Install Retail SDK (Retail POS Plug-ins)](install-retail-sdk-retail-pos-plug-ins.md) and [Retail SDK](retail-sdk.md).

### ![Dn720293.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn720293.collapse_all(en-us,AX.60).gif")Debugging in a browser window

You can debug test, and speed up your webpages by using the F12 developer tools. Open the tools by pressing F12 or by clicking **F12 developer tools** on the **Tools** menu in Internet Explorer. For more information, see [Using the F12 developer tools](http://go.microsoft.com/fwlink/?linkid=335860).

### ![Dn720293.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn720293.collapse_all(en-us,AX.60).gif")Debugging in Visual Studio

To step through code in the online store pages, you must attach the worker process w3wp.exe that runs ASP.NET applications within IIS. To find the worker process, open IIS Manager, select the server name and click **Worker Processes** in the **IIS** section of the **Features View** pane. Then find the worker process that matches the Application Pool for the site. You can use IIS to find the name of the Application Pool for the site, and determine the user that the Application Pool runs under.

  



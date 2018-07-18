---
title: Enterprise Portal administration with Windows PowerShell and AXUpdatePortal
TOCTitle: Enterprise Portal administration with Windows PowerShell and AXUpdatePortal
ms:assetid: b34adf60-46d0-4b8f-8561-b07b5ff41bf4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677310(v=AX.60)
ms:contentKeyID: 49384081
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Enterprise Portal administration with Windows PowerShell and AXUpdatePortal 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can programmatically administer Enterprise Portal for Microsoft Dynamics AX by using PowerShell cmdlets or the AxUpdatePortal utility.

## AXUpdatePortal.exe

The AxUpdatePortal utility, installed with Microsoft Dynamics AX, can be used to deploy Enterprise Portal sites. It can also be used to deploy modifications or additions you have made to existing Enterprise Portal Sites. The utility makes deployment easier, because it can deploy web-related changes to an Enterprise Portal site on an IIS site (virtual server) in just one step. It can also be used to deploy or update specific resources for an Enterprise Portal site. This utility and its parameters are described in detail in the following topic on MSDN, [AxUpdatePortal Utility](https://technet.microsoft.com/en-us/library/dd261467\(v=ax.60\)).

## PowerShell

You can administer Enterprise Portal by using the following PowerShell cmdlets.

## Enable-AXEnterprisePortal

This cmdlet deploys a new virtual server site to an IIS web server that already has Enterprise Portal installed. For more information, see [Enable-AXEnterprisePortal](enable-axenterpriseportal.md).

## Publish-AXWebComponent

This cmdlet enables you to deploy proxies, images, and web components to an Enterprise Portal site. For more information, see [Publish-AXWebComponent](publish-axwebcomponent.md).

## Get-AXWebComponent

This cmdlet returns the web components associated with an Enterprise Portal site in a node of the AOT. For more information, see [Get-AXWebComponent](get-axwebcomponent.md).

## See also

[Administering Microsoft Dynamics AX by using Windows PowerShell](administering-microsoft-dynamics-ax-by-using-windows-powershell.md)

  



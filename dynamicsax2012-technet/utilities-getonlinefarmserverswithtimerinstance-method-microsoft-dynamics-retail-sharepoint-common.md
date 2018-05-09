---
title: Utilities.GetOnlineFarmServersWithTimerInstance Method  (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: GetOnlineFarmServersWithTimerInstance Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.Utilities.GetOnlineFarmServersWithTimerInstance(Microsoft.SharePoint.Administration.SPFarm)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.common.utilities.getonlinefarmserverswithtimerinstance(v=AX.60)
ms:contentKeyID: 62203517
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Common.Utilities.GetOnlineFarmServersWithTimerInstance
dev_langs:
- CSharp
- C++
- VB
---

# GetOnlineFarmServersWithTimerInstance Method

Gets all farm servers that have a timer service online. This is pretty much any server that our code possibly could run on.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetOnlineFarmServersWithTimerInstance ( _
    farm As SPFarm _
) As IEnumerable(Of SPServer)
'Usage
Dim farm As SPFarm
Dim returnValue As IEnumerable(Of SPServer)

returnValue = Utilities.GetOnlineFarmServersWithTimerInstance(farm)
```

``` csharp
public static IEnumerable<SPServer> GetOnlineFarmServersWithTimerInstance(
    SPFarm farm
)
```

``` c++
public:
static IEnumerable<SPServer^>^ GetOnlineFarmServersWithTimerInstance(
    SPFarm^ farm
)
```

#### Parameters

  - farm  
    Type: SPFarm  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<SPServer\>  
An enumeration of SPServer objects.  

## See Also

#### Reference

[Utilities Class](utilities-class-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)


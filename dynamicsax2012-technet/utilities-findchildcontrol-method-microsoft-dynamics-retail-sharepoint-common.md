---
title: Utilities.FindChildControl Method  (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: FindChildControl Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.Utilities.FindChildControl(System.Web.UI.Control,System.Func`2)
ms:mtpsurl: https://technet.microsoft.com/library/Dn694271(v=AX.60)
ms:contentKeyID: 62204695
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Common.Utilities.FindChildControl
dev_langs:
- CSharp
- C++
- VB
---

# FindChildControl Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Function FindChildControl ( _
    rootControl As Control, _
    predicate As Func _
) As Control
'Usage
Dim rootControl As Control
Dim predicate As Func
Dim returnValue As Control

returnValue = Utilities.FindChildControl(rootControl, _
    predicate)
```

``` csharp
public static Control FindChildControl(
    Control rootControl,
    Func predicate
)
```

``` c++
public:
static Control^ FindChildControl(
    Control^ rootControl, 
    Func^ predicate
)
```

#### Parameters

  - rootControl  
    Type: [System.Web.UI.Control](https://technet.microsoft.com/library/983zwx2h\(v=ax.60\))  

<!-- end list -->

  - predicate  
    Type: [System.Func\<T, TResult\>](https://technet.microsoft.com/library/bb549151\(v=ax.60\))  

#### Return Value

Type: [System.Web.UI.Control](https://technet.microsoft.com/library/983zwx2h\(v=ax.60\))  
Returns [Control](https://technet.microsoft.com/library/983zwx2h\(v=ax.60\)).  

## See Also

#### Reference

[Utilities Class](utilities-class-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)


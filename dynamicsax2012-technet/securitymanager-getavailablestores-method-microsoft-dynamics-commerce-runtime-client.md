---
title: SecurityManager.GetAvailableStores Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetAvailableStores Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.SecurityManager.GetAvailableStores(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.securitymanager.getavailablestores(v=AX.60)
ms:contentKeyID: 62204912
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.SecurityManager.GetAvailableStores
dev_langs:
- CSharp
- C++
- VB
---

# GetAvailableStores Method

Get available store(s) for the specific device.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetAvailableStores ( _
    deviceId As String, _
    deviceToken As String _
) As IEnumerable(Of OrgUnit)
'Usage
Dim instance As SecurityManager
Dim deviceId As String
Dim deviceToken As String
Dim returnValue As IEnumerable(Of OrgUnit)

returnValue = instance.GetAvailableStores(deviceId, _
    deviceToken)
```

``` csharp
public IEnumerable<OrgUnit> GetAvailableStores(
    string deviceId,
    string deviceToken
)
```

``` c++
public:
IEnumerable<OrgUnit^>^ GetAvailableStores(
    String^ deviceId, 
    String^ deviceToken
)
```

#### Parameters

  - deviceId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - deviceToken  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[OrgUnit](orgunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The collection of stores.  

## See Also

#### Reference

[SecurityManager Class](securitymanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)


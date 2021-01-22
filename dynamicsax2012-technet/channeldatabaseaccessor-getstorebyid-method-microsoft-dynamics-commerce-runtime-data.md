---
title: ChannelDatabaseAccessor.GetStoreById Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetStoreById Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDatabaseAccessor.GetStoreById(System.Int64)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.channeldatabaseaccessor.getstorebyid(v=AX.60)
ms:contentKeyID: 62210603
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDatabaseAccessor.GetStoreById
dev_langs:
- CSharp
- C++
- VB
---

# GetStoreById Method

Gets the store by channel identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetStoreById ( _
    channelId As Long _
) As OrgUnit
'Usage
Dim instance As ChannelDatabaseAccessor
Dim channelId As Long
Dim returnValue As OrgUnit

returnValue = instance.GetStoreById(channelId)
```

``` csharp
public OrgUnit GetStoreById(
    long channelId
)
```

``` c++
public:
virtual OrgUnit^ GetStoreById(
    long long channelId
) sealed
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnit](orgunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The store or NULL if not found.  

#### Implements

[IChannelDataManager.GetStoreById(Int64)](ichanneldatamanager-getstorebyid-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ChannelDatabaseAccessor Class](channeldatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


---
title: ICachedChannelDataManager.PutStoreById Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutStoreById Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedChannelDataManager.PutStoreById(System.Int64,Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnit)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icachedchanneldatamanager.putstorebyid(v=AX.60)
ms:contentKeyID: 62214350
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedChannelDataManager.PutStoreById
dev_langs:
- CSharp
- C++
- VB
---

# PutStoreById Method

Caches the store by channel identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutStoreById ( _
    channelId As Long, _
    result As OrgUnit _
)
'Usage
Dim instance As ICachedChannelDataManager
Dim channelId As Long
Dim result As OrgUnit

instance.PutStoreById(channelId, result)
```

``` csharp
void PutStoreById(
    long channelId,
    OrgUnit result
)
```

``` c++
void PutStoreById(
    long long channelId, 
    OrgUnit^ result
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - result  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnit](orgunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ICachedChannelDataManager Interface](icachedchanneldatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


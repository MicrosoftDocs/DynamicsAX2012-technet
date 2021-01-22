---
title: ChannelDataManager.GetValidTransactionServiceProfile Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetValidTransactionServiceProfile Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDataManager.GetValidTransactionServiceProfile(Microsoft.Dynamics.Commerce.Runtime.RequestContext)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.channeldatamanager.getvalidtransactionserviceprofile(v=AX.60)
ms:contentKeyID: 65317563
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDataManager.GetValidTransactionServiceProfile
dev_langs:
- CSharp
- C++
- VB
---

# GetValidTransactionServiceProfile Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetValidTransactionServiceProfile ( _
    requestContext As RequestContext _
) As TransactionServiceProfile
'Usage
Dim requestContext As RequestContext
Dim returnValue As TransactionServiceProfile

returnValue = ChannelDataManager.GetValidTransactionServiceProfile(requestContext)
```

``` csharp
public static TransactionServiceProfile GetValidTransactionServiceProfile(
    RequestContext requestContext
)
```

``` c++
public:
static TransactionServiceProfile^ GetValidTransactionServiceProfile(
    RequestContext^ requestContext
)
```

#### Parameters

  - requestContext  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionServiceProfile](transactionserviceprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ChannelDataManager Class](channeldatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


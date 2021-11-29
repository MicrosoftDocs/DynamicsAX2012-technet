---
title: IChannelDataManager.GetDefaultTransactionServiceProfile Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetDefaultTransactionServiceProfile Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IChannelDataManager.GetDefaultTransactionServiceProfile
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.ichanneldatamanager.getdefaulttransactionserviceprofile(v=AX.60)
ms:contentKeyID: 62209261
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IChannelDataManager.GetDefaultTransactionServiceProfile
dev_langs:
- CSharp
- C++
- VB
---

# GetDefaultTransactionServiceProfile Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the default transaction service profile.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Function GetDefaultTransactionServiceProfile As TransactionServiceProfile
'Usage
Dim instance As IChannelDataManager
Dim returnValue As TransactionServiceProfile

returnValue = instance.GetDefaultTransactionServiceProfile()
```

``` csharp
TransactionServiceProfile GetDefaultTransactionServiceProfile()
```

``` c++
TransactionServiceProfile^ GetDefaultTransactionServiceProfile()
```

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionServiceProfile](transactionserviceprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The transaction service profile.  

## See Also

#### Reference

[IChannelDataManager Interface](ichanneldatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


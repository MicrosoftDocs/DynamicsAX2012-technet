---
title: ChannelDataManager.GetDefaultTransactionServiceProfile Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetDefaultTransactionServiceProfile Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDataManager.GetDefaultTransactionServiceProfile
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.channeldatamanager.getdefaulttransactionserviceprofile(v=AX.60)
ms:contentKeyID: 62210958
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDataManager.GetDefaultTransactionServiceProfile
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
Public Function GetDefaultTransactionServiceProfile As TransactionServiceProfile
'Usage
Dim instance As ChannelDataManager
Dim returnValue As TransactionServiceProfile

returnValue = instance.GetDefaultTransactionServiceProfile()
```

``` csharp
public TransactionServiceProfile GetDefaultTransactionServiceProfile()
```

``` c++
public:
virtual TransactionServiceProfile^ GetDefaultTransactionServiceProfile() sealed
```

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionServiceProfile](transactionserviceprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The transaction service profile.  

#### Implements

[IChannelDataManager.GetDefaultTransactionServiceProfile()](ichanneldatamanager-getdefaulttransactionserviceprofile-method-microsoft-dynamics-commerce-runtime-data.md)  

## Remarks

The default transaction service profile can be retrieved based on the setting in Ax RetailSharedParameter table.

## See Also

#### Reference

[ChannelDataManager Class](channeldatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


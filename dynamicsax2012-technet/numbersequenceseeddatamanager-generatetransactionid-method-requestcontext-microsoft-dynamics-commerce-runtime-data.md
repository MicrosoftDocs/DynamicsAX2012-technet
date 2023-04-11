---
title: NumberSequenceSeedDataManager.GenerateTransactionId Method (RequestContext) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GenerateTransactionId Method (RequestContext)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.NumberSequenceSeedDataManager.GenerateTransactionId(Microsoft.Dynamics.Commerce.Runtime.RequestContext)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.numbersequenceseeddatamanager.generatetransactionid(v=AX.60)
ms:contentKeyID: 62213768
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GenerateTransactionId Method (RequestContext)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Generates a new transaction identifier formatted as "StoreId-TerminalId-SequenceNumber".

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GenerateTransactionId ( _
    context As RequestContext _
) As String
'Usage
Dim context As RequestContext
Dim returnValue As String

returnValue = NumberSequenceSeedDataManager.GenerateTransactionId(context)
```

``` csharp
public static string GenerateTransactionId(
    RequestContext context
)
```

``` c++
public:
static String^ GenerateTransactionId(
    RequestContext^ context
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The new transaction identifier.  

## See Also

#### Reference

[NumberSequenceSeedDataManager Class](numbersequenceseeddatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[GenerateTransactionId Overload](numbersequenceseeddatamanager-generatetransactionid-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


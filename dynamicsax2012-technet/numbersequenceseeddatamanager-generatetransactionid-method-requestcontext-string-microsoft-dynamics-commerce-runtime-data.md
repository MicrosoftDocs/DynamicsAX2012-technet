---
title: NumberSequenceSeedDataManager.GenerateTransactionId Method (RequestContext, String) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GenerateTransactionId Method (RequestContext, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.NumberSequenceSeedDataManager.GenerateTransactionId(Microsoft.Dynamics.Commerce.Runtime.RequestContext,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.numbersequenceseeddatamanager.generatetransactionid(v=AX.60)
ms:contentKeyID: 62201802
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GenerateTransactionId Method (RequestContext, String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Generates a new transaction identifier formatted as "StoreId-TerminalId-SequenceNumber".

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GenerateTransactionId ( _
    context As RequestContext, _
    orgUnitNumber As String _
) As String
'Usage
Dim context As RequestContext
Dim orgUnitNumber As String
Dim returnValue As String

returnValue = NumberSequenceSeedDataManager.GenerateTransactionId(context, _
    orgUnitNumber)
```

``` csharp
public static string GenerateTransactionId(
    RequestContext context,
    string orgUnitNumber
)
```

``` c++
public:
static String^ GenerateTransactionId(
    RequestContext^ context, 
    String^ orgUnitNumber
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - orgUnitNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The new transaction identifier.  

## See Also

#### Reference

[NumberSequenceSeedDataManager Class](numbersequenceseeddatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[GenerateTransactionId Overload](numbersequenceseeddatamanager-generatetransactionid-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


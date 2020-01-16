---
title: SerializationHelper.ConvertDateTimeToAXTimeString Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization)
TOCTitle: ConvertDateTimeToAXTimeString Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.SerializationHelper.ConvertDateTimeToAXTimeString(System.DateTime)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.serialization.serializationhelper.convertdatetimetoaxtimestring(v=AX.60)
ms:contentKeyID: 49820229
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.SerializationHelper.ConvertDateTimeToAXTimeString
dev_langs:
- CSharp
- C++
- VB
---

# ConvertDateTimeToAXTimeString Method

Gets the AX time string for given DateTime.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Shared Function ConvertDateTimeToAXTimeString ( _
    date As DateTime _
) As String
'Usage
Dim date As DateTime
Dim returnValue As String

returnValue = SerializationHelper.ConvertDateTimeToAXTimeString(date)
```

``` csharp
public static string ConvertDateTimeToAXTimeString(
    DateTime date
)
```

``` c++
public:
static String^ ConvertDateTimeToAXTimeString(
    DateTime date
)
```

#### Parameters

  - date  
    Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Formated date string according to the date sequence.  

## See Also

#### Reference

[SerializationHelper Class](serializationhelper-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization Namespace](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)


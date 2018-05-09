---
title: SerializationHelper.ConvertDateTimeToAXDateString Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization)
TOCTitle: ConvertDateTimeToAXDateString Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.SerializationHelper.ConvertDateTimeToAXDateString(System.DateTime,System.Int32)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.transactionservice.serialization.serializationhelper.convertdatetimetoaxdatestring(v=AX.60)
ms:contentKeyID: 49835415
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.SerializationHelper.ConvertDateTimeToAXDateString
dev_langs:
- CSharp
- C++
- VB
---

# ConvertDateTimeToAXDateString Method

Gets the AX date string for given DateTime with given AX date sequence format.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Shared Function ConvertDateTimeToAXDateString ( _
    date As DateTime, _
    dateSequence As Integer _
) As String
'Usage
Dim date As DateTime
Dim dateSequence As Integer
Dim returnValue As String

returnValue = SerializationHelper.ConvertDateTimeToAXDateString(date, _
    dateSequence)
```

``` csharp
public static string ConvertDateTimeToAXDateString(
    DateTime date,
    int dateSequence
)
```

``` c++
public:
static String^ ConvertDateTimeToAXDateString(
    DateTime date, 
    int dateSequence
)
```

#### Parameters

  - date  
    Type: [System.DateTime](https://technet.microsoft.com/en-us/library/03ybds8y\(v=ax.60\))  

<!-- end list -->

  - dateSequence  
    Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Formated date string according to the date sequence.  

## See Also

#### Reference

[SerializationHelper Class](serializationhelper-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization Namespace](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)


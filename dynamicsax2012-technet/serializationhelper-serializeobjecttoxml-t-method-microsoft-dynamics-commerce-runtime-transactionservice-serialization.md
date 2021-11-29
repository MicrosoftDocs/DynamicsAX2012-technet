---
title: SerializationHelper.SerializeObjectToXml(T) Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization)
TOCTitle: SerializeObjectToXml(T) Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.SerializationHelper.SerializeObjectToXml``1(``0)
ms:mtpsurl: https://technet.microsoft.com/library/JJ807283(v=AX.60)
ms:contentKeyID: 49855220
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.SerializationHelper.SerializeObjectToXml``1
dev_langs:
- CSharp
- C++
- VB
---

# SerializeObjectToXml(T) Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Serializes object to XML string.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Shared Function SerializeObjectToXml(Of T As Class) ( _
    target As T _
) As String
'Usage
Dim target As T
Dim returnValue As String

returnValue = SerializationHelper.SerializeObjectToXml(target)
```

``` csharp
public static string SerializeObjectToXml<T>(
    T target
)
where T : class
```

``` c++
public:
generic<typename T>
where T : ref class
static String^ SerializeObjectToXml(
    T target
)
```

#### Type Parameters

  - T

#### Parameters

  - target  
    Type: T  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Target serialized in XML string.  

## See Also

#### Reference

[SerializationHelper Class](serializationhelper-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization Namespace](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)


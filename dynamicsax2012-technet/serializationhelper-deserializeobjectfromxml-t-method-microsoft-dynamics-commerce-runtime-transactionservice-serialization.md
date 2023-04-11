---
title: SerializationHelper.DeserializeObjectFromXml(T) Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization)
TOCTitle: DeserializeObjectFromXml(T) Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.SerializationHelper.DeserializeObjectFromXml``1(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/JJ780257(v=AX.60)
ms:contentKeyID: 49839985
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.SerializationHelper.DeserializeObjectFromXml``1
dev_langs:
- CSharp
- C++
- VB
---

# DeserializeObjectFromXml(T) Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Deserializes XML string into object.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Shared Function DeserializeObjectFromXml(Of T As Class) ( _
    source As String _
) As T
'Usage
Dim source As String
Dim returnValue As T

returnValue = SerializationHelper.DeserializeObjectFromXml(source)
```

``` csharp
public static T DeserializeObjectFromXml<T>(
    string source
)
where T : class
```

``` c++
public:
generic<typename T>
where T : ref class
static T DeserializeObjectFromXml(
    String^ source
)
```

#### Type Parameters

  - T

#### Parameters

  - source  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: T  
Deserialized object.  

## See Also

#### Reference

[SerializationHelper Class](serializationhelper-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization Namespace](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)


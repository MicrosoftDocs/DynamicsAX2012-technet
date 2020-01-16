---
title: SerializationHelper.DeserializeObjectDataContractFromByteArray(T) Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization)
TOCTitle: DeserializeObjectDataContractFromByteArray(T) Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.SerializationHelper.DeserializeObjectDataContractFromByteArray``1(System.Byte[])
ms:mtpsurl: https://technet.microsoft.com/library/Dn693974(v=AX.60)
ms:contentKeyID: 62204141
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.SerializationHelper.DeserializeObjectDataContractFromByteArray``1
dev_langs:
- CSharp
- C++
- VB
---

# DeserializeObjectDataContractFromByteArray(T) Method

Deserializes byte array into object.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Shared Function DeserializeObjectDataContractFromByteArray(Of T As Class) ( _
    source As Byte() _
) As T
'Usage
Dim source As Byte()
Dim returnValue As T

returnValue = SerializationHelper.DeserializeObjectDataContractFromByteArray(source)
```

``` csharp
public static T DeserializeObjectDataContractFromByteArray<T>(
    byte[] source
)
where T : class
```

``` c++
public:
generic<typename T>
where T : ref class
static T DeserializeObjectDataContractFromByteArray(
    array<unsigned char>^ source
)
```

#### Type Parameters

  - T

#### Parameters

  - source  
    Type: [System.Byte](https://technet.microsoft.com/library/yyb1w04y\(v=ax.60\))\[\]  

#### Return Value

Type: T  
Deserialized object.  

## See Also

#### Reference

[SerializationHelper Class](serializationhelper-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization Namespace](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)


---
title: SerializationHelper.SerializeObjectToByteArray Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization)
TOCTitle: SerializeObjectToByteArray Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.SerializationHelper.SerializeObjectToByteArray(System.Object)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.transactionservice.serialization.serializationhelper.serializeobjecttobytearray(v=AX.60)
ms:contentKeyID: 62213915
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.SerializationHelper.SerializeObjectToByteArray
dev_langs:
- CSharp
- C++
- VB
---

# SerializeObjectToByteArray Method

Serialize object to byte array.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Shared Function SerializeObjectToByteArray ( _
    target As Object _
) As Byte()
'Usage
Dim target As Object
Dim returnValue As Byte()

returnValue = SerializationHelper.SerializeObjectToByteArray(target)
```

``` csharp
public static byte[] SerializeObjectToByteArray(
    Object target
)
```

``` c++
public:
static array<unsigned char>^ SerializeObjectToByteArray(
    Object^ target
)
```

#### Parameters

  - target  
    Type: [System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  

#### Return Value

Type: [System.Byte](https://technet.microsoft.com/en-us/library/yyb1w04y\(v=ax.60\))\[\]  
The byte array.  

## See Also

#### Reference

[SerializationHelper Class](serializationhelper-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization Namespace](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)


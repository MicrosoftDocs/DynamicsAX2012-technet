---
title: SerializationHelper.SerializeObjectToXml Method (Object) (Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization)
TOCTitle: SerializeObjectToXml Method (Object)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.SerializationHelper.SerializeObjectToXml(System.Object)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.serialization.serializationhelper.serializeobjecttoxml(v=AX.60)
ms:contentKeyID: 49820823
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SerializeObjectToXml Method (Object)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Serializes object to XML string.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Shared Function SerializeObjectToXml ( _
    target As Object _
) As String
'Usage
Dim target As Object
Dim returnValue As String

returnValue = SerializationHelper.SerializeObjectToXml(target)
```

``` csharp
public static string SerializeObjectToXml(
    Object target
)
```

``` c++
public:
static String^ SerializeObjectToXml(
    Object^ target
)
```

#### Parameters

  - target  
    Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Target serialized to xml string.  

## See Also

#### Reference

[SerializationHelper Class](serializationhelper-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)

[SerializeObjectToXml Overload](serializationhelper-serializeobjecttoxml-method-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization Namespace](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)


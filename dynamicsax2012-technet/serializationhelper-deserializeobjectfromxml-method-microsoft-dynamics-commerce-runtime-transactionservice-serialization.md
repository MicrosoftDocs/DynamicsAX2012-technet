---
title: SerializationHelper.DeserializeObjectFromXml Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization)
TOCTitle: DeserializeObjectFromXml Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.SerializationHelper.DeserializeObjectFromXml(System.String,System.Type)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.transactionservice.serialization.serializationhelper.deserializeobjectfromxml(v=AX.60)
ms:contentKeyID: 49843518
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.SerializationHelper.DeserializeObjectFromXml
dev_langs:
- CSharp
- C++
- VB
---

# DeserializeObjectFromXml Method

Deserializes XML string into object.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Shared Function DeserializeObjectFromXml ( _
    source As String, _
    typeInfo As Type _
) As Object
'Usage
Dim source As String
Dim typeInfo As Type
Dim returnValue As Object

returnValue = SerializationHelper.DeserializeObjectFromXml(source, _
    typeInfo)
```

``` csharp
public static Object DeserializeObjectFromXml(
    string source,
    Type typeInfo
)
```

``` c++
public:
static Object^ DeserializeObjectFromXml(
    String^ source, 
    Type^ typeInfo
)
```

#### Parameters

  - source  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - typeInfo  
    Type: [System.Type](https://technet.microsoft.com/en-us/library/42892f65\(v=ax.60\))  

#### Return Value

Type: [System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
Deserialized object.  

## See Also

#### Reference

[SerializationHelper Class](serializationhelper-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization Namespace](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)


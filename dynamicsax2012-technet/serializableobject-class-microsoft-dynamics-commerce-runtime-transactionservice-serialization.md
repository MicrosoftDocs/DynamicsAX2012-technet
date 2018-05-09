---
title: SerializableObject Class (Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization)
TOCTitle: SerializableObject Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.SerializableObject
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.transactionservice.serialization.serializableobject(v=AX.60)
ms:contentKeyID: 49820795
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.SerializableObject
dev_langs:
- CSharp
- C++
- VB
---

# SerializableObject Class

Represents a serializable object.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
<SerializableAttribute> _
Public MustInherit Class SerializableObject
'Usage
Dim instance As SerializableObject
```

``` csharp
[SerializableAttribute]
public abstract class SerializableObject
```

``` c++
[SerializableAttribute]
public ref class SerializableObject abstract
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.SerializableObject  
    [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.CustomerAffiliationInfo](customeraffiliationinfo-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)  
    [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.InventoryInfo](inventoryinfo-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)  
    [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.ItemReturn](itemreturn-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)  
    [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.PickReceiveDocument](pickreceivedocument-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)  
    [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionHeader](transactionheader-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)  
    [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionItem](transactionitem-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization Namespace](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)


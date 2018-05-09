---
title: SaveKitTransactionResponse.KitTransaction Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: KitTransaction Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.SaveKitTransactionResponse.KitTransaction
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.savekittransactionresponse.kittransaction(v=AX.60)
ms:contentKeyID: 62207760
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SaveKitTransactionResponse.KitTransaction
dev_langs:
- CSharp
- C++
- VB
---

# KitTransaction Property

Gets the kit transaction object.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property KitTransaction As KitTransaction
    Get
    Private Set
'Usage
Dim instance As SaveKitTransactionResponse
Dim value As KitTransaction

value = instance.KitTransaction
```

``` csharp
[DataMemberAttribute]
public KitTransaction KitTransaction { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property KitTransaction^ KitTransaction {
    KitTransaction^ get ();
    private: void set (KitTransaction^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.KitTransaction](kittransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [KitTransaction](kittransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[SaveKitTransactionResponse Class](savekittransactionresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


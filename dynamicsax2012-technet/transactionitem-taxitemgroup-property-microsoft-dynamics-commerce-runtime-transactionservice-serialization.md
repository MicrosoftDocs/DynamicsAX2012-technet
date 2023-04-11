---
title: TransactionItem.TaxItemGroup Property  (Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization)
TOCTitle: TaxItemGroup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionItem.TaxItemGroup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.serialization.transactionitem.taxitemgroup(v=AX.60)
ms:contentKeyID: 49832365
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionItem.TaxItemGroup
dev_langs:
- CSharp
- C++
- VB
---

# TaxItemGroup Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the tax item group.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property TaxItemGroup As String
    Get
    Set
'Usage
Dim instance As TransactionItem
Dim value As String

value = instance.TaxItemGroup

instance.TaxItemGroup = value
```

``` csharp
public string TaxItemGroup { get; set; }
```

``` c++
public:
property String^ TaxItemGroup {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The tax item group.  

## See Also

#### Reference

[TransactionItem Class](transactionitem-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization Namespace](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)


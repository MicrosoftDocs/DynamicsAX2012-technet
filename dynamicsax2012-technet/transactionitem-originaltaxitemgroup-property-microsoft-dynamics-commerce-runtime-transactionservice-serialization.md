---
title: TransactionItem.OriginalTaxItemGroup Property  (Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization)
TOCTitle: OriginalTaxItemGroup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionItem.OriginalTaxItemGroup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.serialization.transactionitem.originaltaxitemgroup(v=AX.60)
ms:contentKeyID: 49847473
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionItem.OriginalTaxItemGroup
dev_langs:
- CSharp
- C++
- VB
---

# OriginalTaxItemGroup Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the original tax item group.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property OriginalTaxItemGroup As String
    Get
    Set
'Usage
Dim instance As TransactionItem
Dim value As String

value = instance.OriginalTaxItemGroup

instance.OriginalTaxItemGroup = value
```

``` csharp
public string OriginalTaxItemGroup { get; set; }
```

``` c++
public:
property String^ OriginalTaxItemGroup {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The original tax item group.  

## See Also

#### Reference

[TransactionItem Class](transactionitem-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization Namespace](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)


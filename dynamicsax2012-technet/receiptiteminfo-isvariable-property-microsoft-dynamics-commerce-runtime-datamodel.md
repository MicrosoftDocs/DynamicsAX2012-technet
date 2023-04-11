---
title: ReceiptItemInfo.IsVariable Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsVariable Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptItemInfo.IsVariable
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.receiptiteminfo.isvariable(v=AX.60)
ms:contentKeyID: 62212105
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptItemInfo.IsVariable
dev_langs:
- CSharp
- C++
- VB
---

# IsVariable Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether a tag is a variable in the template.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Property IsVariable As Boolean
    Get
    Set
'Usage
Dim instance As ReceiptItemInfo
Dim value As Boolean

value = instance.IsVariable

instance.IsVariable = value
```

``` csharp
public bool IsVariable { get; set; }
```

``` c++
public:
property bool IsVariable {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ReceiptItemInfo Class](receiptiteminfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


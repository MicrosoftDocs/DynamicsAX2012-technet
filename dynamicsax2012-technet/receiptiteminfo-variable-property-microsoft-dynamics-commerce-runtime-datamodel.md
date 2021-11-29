---
title: ReceiptItemInfo.Variable Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Variable Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptItemInfo.Variable
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.receiptiteminfo.variable(v=AX.60)
ms:contentKeyID: 62208717
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptItemInfo.Variable
dev_langs:
- CSharp
- C++
- VB
---

# Variable Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets property for Variable.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Property Variable As String
    Get
    Set
'Usage
Dim instance As ReceiptItemInfo
Dim value As String

value = instance.Variable

instance.Variable = value
```

``` csharp
public string Variable { get; set; }
```

``` c++
public:
property String^ Variable {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ReceiptItemInfo Class](receiptiteminfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


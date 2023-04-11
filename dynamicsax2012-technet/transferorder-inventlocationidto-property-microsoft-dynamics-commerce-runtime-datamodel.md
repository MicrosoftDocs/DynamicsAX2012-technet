---
title: TransferOrder.InventLocationIdTo Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InventLocationIdTo Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TransferOrder.InventLocationIdTo
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.transferorder.inventlocationidto(v=AX.60)
ms:contentKeyID: 62208614
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransferOrder.InventLocationIdTo
dev_langs:
- CSharp
- C++
- VB
---

# InventLocationIdTo Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the to location of the transfer order.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property InventLocationIdTo As String
    Get
    Set
'Usage
Dim instance As TransferOrder
Dim value As String

value = instance.InventLocationIdTo

instance.InventLocationIdTo = value
```

``` csharp
[DataMemberAttribute]
public string InventLocationIdTo { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ InventLocationIdTo {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TransferOrder Class](transferorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


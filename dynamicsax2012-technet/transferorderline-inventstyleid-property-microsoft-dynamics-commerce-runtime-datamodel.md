---
title: TransferOrderLine.InventStyleId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InventStyleId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TransferOrderLine.InventStyleId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.transferorderline.inventstyleid(v=AX.60)
ms:contentKeyID: 62210382
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransferOrderLine.InventStyleId
dev_langs:
- CSharp
- C++
- VB
---

# InventStyleId Property

Gets or sets the inventory style identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("INVENTSTYLEID")> _
Public Property InventStyleId As String
    Get
    Set
'Usage
Dim instance As TransferOrderLine
Dim value As String

value = instance.InventStyleId

instance.InventStyleId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("INVENTSTYLEID")]
public string InventStyleId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"INVENTSTYLEID")]
public:
property String^ InventStyleId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TransferOrderLine Class](transferorderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


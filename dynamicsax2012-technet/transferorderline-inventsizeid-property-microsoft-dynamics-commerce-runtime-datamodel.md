---
title: TransferOrderLine.InventSizeId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InventSizeId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TransferOrderLine.InventSizeId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.transferorderline.inventsizeid(v=AX.60)
ms:contentKeyID: 62209876
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransferOrderLine.InventSizeId
dev_langs:
- CSharp
- C++
- VB
---

# InventSizeId Property

Gets or sets the inventory size identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("INVENTSIZEID")> _
Public Property InventSizeId As String
    Get
    Set
'Usage
Dim instance As TransferOrderLine
Dim value As String

value = instance.InventSizeId

instance.InventSizeId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("INVENTSIZEID")]
public string InventSizeId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"INVENTSIZEID")]
public:
property String^ InventSizeId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TransferOrderLine Class](transferorderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


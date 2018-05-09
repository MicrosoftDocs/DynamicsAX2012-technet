---
title: PurchaseOrderLine.InventColorId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InventColorId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PurchaseOrderLine.InventColorId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.purchaseorderline.inventcolorid(v=AX.60)
ms:contentKeyID: 62208853
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PurchaseOrderLine.InventColorId
dev_langs:
- CSharp
- C++
- VB
---

# InventColorId Property

Gets or sets the inventory color identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("INVENTCOLORID")> _
Public Property InventColorId As String
    Get
    Set
'Usage
Dim instance As PurchaseOrderLine
Dim value As String

value = instance.InventColorId

instance.InventColorId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("INVENTCOLORID")]
public string InventColorId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"INVENTCOLORID")]
public:
property String^ InventColorId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[PurchaseOrderLine Class](purchaseorderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


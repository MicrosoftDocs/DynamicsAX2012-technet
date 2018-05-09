---
title: PurchaseOrderLine.InventSerialId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InventSerialId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PurchaseOrderLine.InventSerialId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.purchaseorderline.inventserialid(v=AX.60)
ms:contentKeyID: 62213497
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PurchaseOrderLine.InventSerialId
dev_langs:
- CSharp
- C++
- VB
---

# InventSerialId Property

Gets or sets the inventory serial identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("INVENTSERIALID")> _
<DataMemberAttribute> _
Public Property InventSerialId As String
    Get
    Set
'Usage
Dim instance As PurchaseOrderLine
Dim value As String

value = instance.InventSerialId

instance.InventSerialId = value
```

``` csharp
[ColumnAttribute("INVENTSERIALID")]
[DataMemberAttribute]
public string InventSerialId { get; set; }
```

``` c++
[ColumnAttribute(L"INVENTSERIALID")]
[DataMemberAttribute]
public:
property String^ InventSerialId {
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


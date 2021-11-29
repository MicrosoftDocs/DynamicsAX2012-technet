---
title: PurchaseOrderLine.InventBatchId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InventBatchId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PurchaseOrderLine.InventBatchId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.purchaseorderline.inventbatchid(v=AX.60)
ms:contentKeyID: 62213937
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PurchaseOrderLine.InventBatchId
dev_langs:
- CSharp
- C++
- VB
---

# InventBatchId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the inventory batch identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("INVENTBATCHID")> _
Public Property InventBatchId As String
    Get
    Set
'Usage
Dim instance As PurchaseOrderLine
Dim value As String

value = instance.InventBatchId

instance.InventBatchId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("INVENTBATCHID")]
public string InventBatchId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"INVENTBATCHID")]
public:
property String^ InventBatchId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[PurchaseOrderLine Class](purchaseorderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


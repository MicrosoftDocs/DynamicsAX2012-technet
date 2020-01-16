---
title: PurchaseOrderLine.PurchaseUnit Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PurchaseUnit Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PurchaseOrderLine.PurchaseUnit
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.purchaseorderline.purchaseunit(v=AX.60)
ms:contentKeyID: 62210475
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PurchaseOrderLine.PurchaseUnit
dev_langs:
- CSharp
- C++
- VB
---

# PurchaseUnit Property

Gets or sets the purchase unit.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PURCHASEUNIT")> _
<DataMemberAttribute> _
Public Property PurchaseUnit As String
    Get
    Set
'Usage
Dim instance As PurchaseOrderLine
Dim value As String

value = instance.PurchaseUnit

instance.PurchaseUnit = value
```

``` csharp
[ColumnAttribute("PURCHASEUNIT")]
[DataMemberAttribute]
public string PurchaseUnit { get; set; }
```

``` c++
[ColumnAttribute(L"PURCHASEUNIT")]
[DataMemberAttribute]
public:
property String^ PurchaseUnit {
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


---
title: CartLineData.ReturnInventoryTransactionId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReturnInventoryTransactionId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.ReturnInventoryTransactionId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.cartlinedata.returninventorytransactionid(v=AX.60)
ms:contentKeyID: 62209179
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.ReturnInventoryTransactionId
dev_langs:
- CSharp
- C++
- VB
---

# ReturnInventoryTransactionId Property

Gets or sets the invent trans id related to this return line (customer order).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("RETURNINVENTTRANSID")> _
<DataMemberAttribute> _
Public Property ReturnInventoryTransactionId As String
    Get
    Set
'Usage
Dim instance As CartLineData
Dim value As String

value = instance.ReturnInventoryTransactionId

instance.ReturnInventoryTransactionId = value
```

``` csharp
[ColumnAttribute("RETURNINVENTTRANSID")]
[DataMemberAttribute]
public string ReturnInventoryTransactionId { get; set; }
```

``` c++
[ColumnAttribute(L"RETURNINVENTTRANSID")]
[DataMemberAttribute]
public:
property String^ ReturnInventoryTransactionId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CartLineData Class](cartlinedata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


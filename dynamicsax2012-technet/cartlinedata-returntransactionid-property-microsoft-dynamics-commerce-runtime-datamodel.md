---
title: CartLineData.ReturnTransactionId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReturnTransactionId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.ReturnTransactionId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.cartlinedata.returntransactionid(v=AX.60)
ms:contentKeyID: 62209257
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.ReturnTransactionId
dev_langs:
- CSharp
- C++
- VB
---

# ReturnTransactionId Property

Gets or sets the returned transaction identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("RETURNTRANSACTIONID")> _
Public Property ReturnTransactionId As String
    Get
    Set
'Usage
Dim instance As CartLineData
Dim value As String

value = instance.ReturnTransactionId

instance.ReturnTransactionId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("RETURNTRANSACTIONID")]
public string ReturnTransactionId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"RETURNTRANSACTIONID")]
public:
property String^ ReturnTransactionId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The transaction identifier.  

## See Also

#### Reference

[CartLineData Class](cartlinedata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


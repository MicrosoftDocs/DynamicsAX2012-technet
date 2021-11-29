---
title: SalesTransaction.IsTaxIncludedInPrice Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsTaxIncludedInPrice Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.IsTaxIncludedInPrice
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.istaxincludedinprice(v=AX.60)
ms:contentKeyID: 49827314
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.IsTaxIncludedInPrice
dev_langs:
- CSharp
- C++
- VB
---

# IsTaxIncludedInPrice Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether the tax is included in the item price.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ISTAXINCLUDEDINPRICE")> _
<DataMemberAttribute> _
Public Property IsTaxIncludedInPrice As Boolean
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As Boolean

value = instance.IsTaxIncludedInPrice

instance.IsTaxIncludedInPrice = value
```

``` csharp
[ColumnAttribute("ISTAXINCLUDEDINPRICE")]
[DataMemberAttribute]
public bool IsTaxIncludedInPrice { get; set; }
```

``` c++
[ColumnAttribute(L"ISTAXINCLUDEDINPRICE")]
[DataMemberAttribute]
public:
property bool IsTaxIncludedInPrice {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


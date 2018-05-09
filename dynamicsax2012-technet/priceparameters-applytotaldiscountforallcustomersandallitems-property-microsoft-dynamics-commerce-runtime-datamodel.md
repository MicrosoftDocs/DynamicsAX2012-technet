---
title: PriceParameters.ApplyTotalDiscountForAllCustomersAndAllItems Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ApplyTotalDiscountForAllCustomersAndAllItems Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters.ApplyTotalDiscountForAllCustomersAndAllItems
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.priceparameters.applytotaldiscountforallcustomersandallitems(v=AX.60)
ms:contentKeyID: 49842708
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters.ApplyTotalDiscountForAllCustomersAndAllItems
dev_langs:
- CSharp
- C++
- VB
---

# ApplyTotalDiscountForAllCustomersAndAllItems Property

Gets a value indicating whether total discount trade agreement should apply for combination of all customers and all items.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SALESENDALLALL")> _
Public Property ApplyTotalDiscountForAllCustomersAndAllItems As Boolean
    Get
    Friend Set
'Usage
Dim instance As PriceParameters
Dim value As Boolean

value = instance.ApplyTotalDiscountForAllCustomersAndAllItems
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SALESENDALLALL")]
public bool ApplyTotalDiscountForAllCustomersAndAllItems { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SALESENDALLALL")]
public:
property bool ApplyTotalDiscountForAllCustomersAndAllItems {
    bool get ();
    internal: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[PriceParameters Class](priceparameters-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


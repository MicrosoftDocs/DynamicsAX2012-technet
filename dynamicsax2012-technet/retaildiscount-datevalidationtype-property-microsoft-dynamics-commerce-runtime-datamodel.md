---
title: RetailDiscount.DateValidationType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DateValidationType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscount.DateValidationType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.retaildiscount.datevalidationtype(v=AX.60)
ms:contentKeyID: 62212453
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscount.DateValidationType
dev_langs:
- CSharp
- C++
- VB
---

# DateValidationType Property

Gets or sets the date validation type (standard or advanced) for the discount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DATEVALIDATIONTYPE")> _
<DataMemberAttribute> _
Public Property DateValidationType As Integer
    Get
    Set
'Usage
Dim instance As RetailDiscount
Dim value As Integer

value = instance.DateValidationType

instance.DateValidationType = value
```

``` csharp
[ColumnAttribute("DATEVALIDATIONTYPE")]
[DataMemberAttribute]
public int DateValidationType { get; set; }
```

``` c++
[ColumnAttribute(L"DATEVALIDATIONTYPE")]
[DataMemberAttribute]
public:
property int DateValidationType {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[RetailDiscount Class](retaildiscount-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


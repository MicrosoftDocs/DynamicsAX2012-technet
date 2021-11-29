---
title: RetailDiscount.ValidationPeriodId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ValidationPeriodId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscount.ValidationPeriodId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.retaildiscount.validationperiodid(v=AX.60)
ms:contentKeyID: 62211742
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscount.ValidationPeriodId
dev_langs:
- CSharp
- C++
- VB
---

# ValidationPeriodId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the validation period identifier if using advanced date validation.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("VALIDATIONPERIODID")> _
<DataMemberAttribute> _
Public Property ValidationPeriodId As String
    Get
    Set
'Usage
Dim instance As RetailDiscount
Dim value As String

value = instance.ValidationPeriodId

instance.ValidationPeriodId = value
```

``` csharp
[ColumnAttribute("VALIDATIONPERIODID")]
[DataMemberAttribute]
public string ValidationPeriodId { get; set; }
```

``` c++
[ColumnAttribute(L"VALIDATIONPERIODID")]
[DataMemberAttribute]
public:
property String^ ValidationPeriodId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[RetailDiscount Class](retaildiscount-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


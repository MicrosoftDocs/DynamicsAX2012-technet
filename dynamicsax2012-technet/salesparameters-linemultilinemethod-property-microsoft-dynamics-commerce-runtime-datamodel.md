---
title: SalesParameters.LineMultilineMethod Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LineMultilineMethod Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesParameters.LineMultilineMethod
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesparameters.linemultilinemethod(v=AX.60)
ms:contentKeyID: 51677234
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesParameters.LineMultilineMethod
dev_langs:
- CSharp
- C++
- VB
---

# LineMultilineMethod Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating how to combine trade agreement line and multiline discounts on a sales line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("DISC")> _
Public Property LineMultilineMethod As LineDiscountCalculationType
    Get
    Friend Set
'Usage
Dim instance As SalesParameters
Dim value As LineDiscountCalculationType

value = instance.LineMultilineMethod
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("DISC")]
public LineDiscountCalculationType LineMultilineMethod { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"DISC")]
public:
property LineDiscountCalculationType LineMultilineMethod {
    LineDiscountCalculationType get ();
    internal: void set (LineDiscountCalculationType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.LineDiscountCalculationType](linediscountcalculationtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [LineDiscountCalculationType](linediscountcalculationtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[SalesParameters Class](salesparameters-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


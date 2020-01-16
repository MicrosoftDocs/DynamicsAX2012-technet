---
title: SalesLine.LineMultilineDiscOnItemValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LineMultilineDiscOnItemValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.LineMultilineDiscOnItemValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.linemultilinedisconitemvalue(v=AX.60)
ms:contentKeyID: 62203110
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.LineMultilineDiscOnItemValue
dev_langs:
- CSharp
- C++
- VB
---

# LineMultilineDiscOnItemValue Property

Gets or sets the value of the LineMultilineDiscountOnItem enum. Used by OData only.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LineMultilineDiscOnItemValue As Integer
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As Integer

value = instance.LineMultilineDiscOnItemValue

instance.LineMultilineDiscOnItemValue = value
```

``` csharp
[DataMemberAttribute]
public int LineMultilineDiscOnItemValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int LineMultilineDiscOnItemValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


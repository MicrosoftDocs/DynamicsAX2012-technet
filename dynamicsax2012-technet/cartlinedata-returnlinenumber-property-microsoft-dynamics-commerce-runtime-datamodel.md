---
title: CartLineData.ReturnLineNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReturnLineNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.ReturnLineNumber
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.cartlinedata.returnlinenumber(v=AX.60)
ms:contentKeyID: 62206638
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.ReturnLineNumber
dev_langs:
- CSharp
- C++
- VB
---

# ReturnLineNumber Property

Gets or sets the sales line number of the returned transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("RETURNLINENUM")> _
Public Property ReturnLineNumber As Decimal
    Get
    Set
'Usage
Dim instance As CartLineData
Dim value As Decimal

value = instance.ReturnLineNumber

instance.ReturnLineNumber = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("RETURNLINENUM")]
public decimal ReturnLineNumber { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"RETURNLINENUM")]
public:
property Decimal ReturnLineNumber {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
The line number.  

## See Also

#### Reference

[CartLineData Class](cartlinedata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


---
title: CartLine.ReturnLineNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReturnLineNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.ReturnLineNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartline.returnlinenumber(v=AX.60)
ms:contentKeyID: 62213018
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.ReturnLineNumber
dev_langs:
- CSharp
- C++
- VB
---

# ReturnLineNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the sales line number of the returned transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ReturnLineNumber As Decimal
    Get
    Set
'Usage
Dim instance As CartLine
Dim value As Decimal

value = instance.ReturnLineNumber

instance.ReturnLineNumber = value
```

``` csharp
[DataMemberAttribute]
public decimal ReturnLineNumber { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal ReturnLineNumber {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The line number.  

## See Also

#### Reference

[CartLine Class](cartline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


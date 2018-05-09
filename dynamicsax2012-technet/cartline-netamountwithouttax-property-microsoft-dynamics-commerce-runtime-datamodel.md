---
title: CartLine.NetAmountWithoutTax Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: NetAmountWithoutTax Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.NetAmountWithoutTax
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.cartline.netamountwithouttax(v=AX.60)
ms:contentKeyID: 65321331
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.NetAmountWithoutTax
dev_langs:
- CSharp
- C++
- VB
---

# NetAmountWithoutTax Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property NetAmountWithoutTax As Decimal
    Get
    Set
'Usage
Dim instance As CartLine
Dim value As Decimal

value = instance.NetAmountWithoutTax

instance.NetAmountWithoutTax = value
```

``` csharp
[DataMemberAttribute]
public decimal NetAmountWithoutTax { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal NetAmountWithoutTax {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[CartLine Class](cartline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


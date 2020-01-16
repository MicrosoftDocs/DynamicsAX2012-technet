---
title: SaveCartRequest.CalculationModes Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: CalculationModes Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.SaveCartRequest.CalculationModes
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.savecartrequest.calculationmodes(v=AX.60)
ms:contentKeyID: 62209631
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SaveCartRequest.CalculationModes
dev_langs:
- CSharp
- C++
- VB
---

# CalculationModes Property

Gets the amounts to be calculated after the cart has been saved.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CalculationModes As Nullable(Of CalculationModes)
    Get
    Private Set
'Usage
Dim instance As SaveCartRequest
Dim value As Nullable(Of CalculationModes)

value = instance.CalculationModes
```

``` csharp
[DataMemberAttribute]
public Nullable<CalculationModes> CalculationModes { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Nullable<CalculationModes> CalculationModes {
    Nullable<CalculationModes> get ();
    private: void set (Nullable<CalculationModes> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[CalculationModes](calculationmodes-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [Nullable\<T\>](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\)).  

## See Also

#### Reference

[SaveCartRequest Class](savecartrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


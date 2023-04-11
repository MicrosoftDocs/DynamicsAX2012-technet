---
title: ChargeLine.ChargeMethod Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ChargeMethod Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeLine.ChargeMethod
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.chargeline.chargemethod(v=AX.60)
ms:contentKeyID: 49856234
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeLine.ChargeMethod
dev_langs:
- CSharp
- C++
- VB
---

# ChargeMethod Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the method for computing this charge line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property ChargeMethod As ChargeMethod
    Get
    Set
'Usage
Dim instance As ChargeLine
Dim value As ChargeMethod

value = instance.ChargeMethod

instance.ChargeMethod = value
```

``` csharp
[IgnoreDataMemberAttribute]
public ChargeMethod ChargeMethod { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property ChargeMethod ChargeMethod {
    ChargeMethod get ();
    void set (ChargeMethod value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeMethod](chargemethod-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
The charge method.  

## Remarks

Charge computation methods include: fixed, percent, pieces, and external charges.

## See Also

#### Reference

[ChargeLine Class](chargeline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


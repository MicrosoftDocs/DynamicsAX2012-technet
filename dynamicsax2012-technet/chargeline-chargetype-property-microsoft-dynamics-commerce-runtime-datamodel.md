---
title: ChargeLine.ChargeType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ChargeType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeLine.ChargeType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.chargeline.chargetype(v=AX.60)
ms:contentKeyID: 49823495
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeLine.ChargeType
dev_langs:
- CSharp
- C++
- VB
---

# ChargeType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the kind of charge based on which rules created it.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property ChargeType As ChargeType
    Get
    Set
'Usage
Dim instance As ChargeLine
Dim value As ChargeType

value = instance.ChargeType

instance.ChargeType = value
```

``` csharp
[IgnoreDataMemberAttribute]
public ChargeType ChargeType { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property ChargeType ChargeType {
    ChargeType get ();
    void set (ChargeType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeType](chargetype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
The type of the charge.  

## See Also

#### Reference

[ChargeLine Class](chargeline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


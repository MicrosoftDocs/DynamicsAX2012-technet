---
title: GetCartRequest.CalculationModes Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: CalculationModes Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetCartRequest.CalculationModes
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getcartrequest.calculationmodes(v=AX.60)
ms:contentKeyID: 49851721
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetCartRequest.CalculationModes
dev_langs:
- CSharp
- C++
- VB
---

# CalculationModes Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the calculation modes.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CalculationModes As CalculationModes
    Get
    Set
'Usage
Dim instance As GetCartRequest
Dim value As CalculationModes

value = instance.CalculationModes

instance.CalculationModes = value
```

``` csharp
[DataMemberAttribute]
public CalculationModes CalculationModes { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property CalculationModes CalculationModes {
    CalculationModes get ();
    void set (CalculationModes value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CalculationModes](calculationmodes-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [CalculationModes](calculationmodes-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetCartRequest Class](getcartrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


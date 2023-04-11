---
title: ChargeLine.ChargeMethodValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ChargeMethodValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeLine.ChargeMethodValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.chargeline.chargemethodvalue(v=AX.60)
ms:contentKeyID: 62214944
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeLine.ChargeMethodValue
dev_langs:
- CSharp
- C++
- VB
---

# ChargeMethodValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the value of the ChargeMethod enum. Used by OData only.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ChargeMethodValue As Integer
    Get
    Set
'Usage
Dim instance As ChargeLine
Dim value As Integer

value = instance.ChargeMethodValue

instance.ChargeMethodValue = value
```

``` csharp
[DataMemberAttribute]
public int ChargeMethodValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int ChargeMethodValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[ChargeLine Class](chargeline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


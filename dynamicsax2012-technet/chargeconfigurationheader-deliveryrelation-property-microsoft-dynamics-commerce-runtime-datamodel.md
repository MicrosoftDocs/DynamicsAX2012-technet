---
title: ChargeConfigurationHeader.DeliveryRelation Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DeliveryRelation Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfigurationHeader.DeliveryRelation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.chargeconfigurationheader.deliveryrelation(v=AX.60)
ms:contentKeyID: 49823048
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfigurationHeader.DeliveryRelation
dev_langs:
- CSharp
- C++
- VB
---

# DeliveryRelation Property

Gets or sets the delivery mode identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Property DeliveryRelation As String
    Get
    Set
'Usage
Dim instance As ChargeConfigurationHeader
Dim value As String

value = instance.DeliveryRelation

instance.DeliveryRelation = value
```

``` csharp
public string DeliveryRelation { get; set; }
```

``` c++
public:
property String^ DeliveryRelation {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## Remarks

This value can be delivery mode code, charge group id, or blank (for all DeliveryTypes respectively).

## See Also

#### Reference

[ChargeConfigurationHeader Class](chargeconfigurationheader-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


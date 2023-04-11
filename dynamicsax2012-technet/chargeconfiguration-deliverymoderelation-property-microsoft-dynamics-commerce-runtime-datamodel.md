---
title: ChargeConfiguration.DeliveryModeRelation Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DeliveryModeRelation Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfiguration.DeliveryModeRelation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.chargeconfiguration.deliverymoderelation(v=AX.60)
ms:contentKeyID: 49833899
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfiguration.DeliveryModeRelation
dev_langs:
- CSharp
- C++
- VB
---

# DeliveryModeRelation Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the delivery mode or delivery mode charge group.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DLVMODERELATION")> _
<DataMemberAttribute> _
Public Property DeliveryModeRelation As String
    Get
    Set
'Usage
Dim instance As ChargeConfiguration
Dim value As String

value = instance.DeliveryModeRelation

instance.DeliveryModeRelation = value
```

``` csharp
[ColumnAttribute("DLVMODERELATION")]
[DataMemberAttribute]
public string DeliveryModeRelation { get; set; }
```

``` c++
[ColumnAttribute(L"DLVMODERELATION")]
[DataMemberAttribute]
public:
property String^ DeliveryModeRelation {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ChargeConfiguration Class](chargeconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


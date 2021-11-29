---
title: DeliveryOption.ChargeGroup Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ChargeGroup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeliveryOption.ChargeGroup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deliveryoption.chargegroup(v=AX.60)
ms:contentKeyID: 49854439
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeliveryOption.ChargeGroup
dev_langs:
- CSharp
- C++
- VB
---

# ChargeGroup Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the charge group identifier that this delivery mode is assigned to.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("MARKUPGROUP")> _
Public Property ChargeGroup As String
    Get
    Friend Set
'Usage
Dim instance As DeliveryOption
Dim value As String

value = instance.ChargeGroup
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("MARKUPGROUP")]
public string ChargeGroup { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"MARKUPGROUP")]
public:
property String^ ChargeGroup {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[DeliveryOption Class](deliveryoption-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


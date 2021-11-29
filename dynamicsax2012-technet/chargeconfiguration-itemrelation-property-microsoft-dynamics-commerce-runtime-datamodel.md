---
title: ChargeConfiguration.ItemRelation Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ItemRelation Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfiguration.ItemRelation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.chargeconfiguration.itemrelation(v=AX.60)
ms:contentKeyID: 49852623
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfiguration.ItemRelation
dev_langs:
- CSharp
- C++
- VB
---

# ItemRelation Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the item or item charge group for the configuration.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ITEMRELATION")> _
Public Property ItemRelation As String
    Get
    Set
'Usage
Dim instance As ChargeConfiguration
Dim value As String

value = instance.ItemRelation

instance.ItemRelation = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ITEMRELATION")]
public string ItemRelation { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ITEMRELATION")]
public:
property String^ ItemRelation {
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


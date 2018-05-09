---
title: ChargeConfigurationHeader.ItemRelation Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ItemRelation Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfigurationHeader.ItemRelation
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.chargeconfigurationheader.itemrelation(v=AX.60)
ms:contentKeyID: 49851041
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfigurationHeader.ItemRelation
dev_langs:
- CSharp
- C++
- VB
---

# ItemRelation Property

Gets or sets the item identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Property ItemRelation As String
    Get
    Set
'Usage
Dim instance As ChargeConfigurationHeader
Dim value As String

value = instance.ItemRelation

instance.ItemRelation = value
```

``` csharp
public string ItemRelation { get; set; }
```

``` c++
public:
property String^ ItemRelation {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## Remarks

This value can be item id, charge group id, or blank (for all ItemTypes, respectively).

## See Also

#### Reference

[ChargeConfigurationHeader Class](chargeconfigurationheader-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


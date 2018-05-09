---
title: TillLayout.ButtonGridZones Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ButtonGridZones Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TillLayout.ButtonGridZones
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.tilllayout.buttongridzones(v=AX.60)
ms:contentKeyID: 62214532
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TillLayout.ButtonGridZones
dev_langs:
- CSharp
- C++
- VB
---

# ButtonGridZones Property

Gets the collection of button grid zones.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ButtonGridZones As ICollection(Of ButtonGridZone)
    Get
    Set
'Usage
Dim instance As TillLayout
Dim value As ICollection(Of ButtonGridZone)

value = instance.ButtonGridZones

instance.ButtonGridZones = value
```

``` csharp
[DataMemberAttribute]
public ICollection<ButtonGridZone> ButtonGridZones { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<ButtonGridZone^>^ ButtonGridZones {
    ICollection<ButtonGridZone^>^ get ();
    void set (ICollection<ButtonGridZone^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/en-us/library/92t2ye13\(v=ax.60\))\<[ButtonGridZone](buttongridzone-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/en-us/library/92t2ye13\(v=ax.60\)).  

## See Also

#### Reference

[TillLayout Class](tilllayout-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


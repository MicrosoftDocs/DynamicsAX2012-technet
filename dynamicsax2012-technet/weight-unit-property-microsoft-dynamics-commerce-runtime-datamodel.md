---
title: Weight.Unit Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Unit Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Weight.Unit
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.weight.unit(v=AX.60)
ms:contentKeyID: 49844073
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Weight.Unit
dev_langs:
- CSharp
- C++
- VB
---

# Unit Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the unit.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Unit As String
    Get
    Set
'Usage
Dim instance As Weight
Dim value As String

value = instance.Unit

instance.Unit = value
```

``` csharp
[DataMemberAttribute]
public string Unit { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Unit {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The units of measurement.  

## See Also

#### Reference

[Weight Class](weight-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


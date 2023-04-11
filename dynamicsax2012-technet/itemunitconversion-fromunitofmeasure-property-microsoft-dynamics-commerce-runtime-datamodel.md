---
title: ItemUnitConversion.FromUnitOfMeasure Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FromUnitOfMeasure Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemUnitConversion.FromUnitOfMeasure
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.itemunitconversion.fromunitofmeasure(v=AX.60)
ms:contentKeyID: 49819202
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemUnitConversion.FromUnitOfMeasure
dev_langs:
- CSharp
- C++
- VB
---

# FromUnitOfMeasure Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the unit of measure to convert from.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property FromUnitOfMeasure As String
    Get
    Set
'Usage
Dim instance As ItemUnitConversion
Dim value As String

value = instance.FromUnitOfMeasure

instance.FromUnitOfMeasure = value
```

``` csharp
[DataMemberAttribute]
public string FromUnitOfMeasure { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ FromUnitOfMeasure {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The unit of measure.  

## See Also

#### Reference

[ItemUnitConversion Class](itemunitconversion-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


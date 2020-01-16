---
title: ItemUnitConversion.ToUnitOfMeasure Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ToUnitOfMeasure Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemUnitConversion.ToUnitOfMeasure
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.itemunitconversion.tounitofmeasure(v=AX.60)
ms:contentKeyID: 49820233
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemUnitConversion.ToUnitOfMeasure
dev_langs:
- CSharp
- C++
- VB
---

# ToUnitOfMeasure Property

Gets or sets the unit of measure to convert to.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ToUnitOfMeasure As String
    Get
    Set
'Usage
Dim instance As ItemUnitConversion
Dim value As String

value = instance.ToUnitOfMeasure

instance.ToUnitOfMeasure = value
```

``` csharp
[DataMemberAttribute]
public string ToUnitOfMeasure { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ToUnitOfMeasure {
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


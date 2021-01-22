---
title: AttributeIntValue.UnitSymbol Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: UnitSymbol Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeIntValue.UnitSymbol
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.attributeintvalue.unitsymbol(v=AX.60)
ms:contentKeyID: 49841428
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeIntValue.UnitSymbol
dev_langs:
- CSharp
- C++
- VB
---

# UnitSymbol Property

Gets or sets the unit symbol.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property UnitSymbol As String
    Get
    Set
'Usage
Dim instance As AttributeIntValue
Dim value As String

value = instance.UnitSymbol

instance.UnitSymbol = value
```

``` csharp
[DataMemberAttribute]
public string UnitSymbol { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ UnitSymbol {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The unit symbol.  

## See Also

#### Reference

[AttributeIntValue Class](attributeintvalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


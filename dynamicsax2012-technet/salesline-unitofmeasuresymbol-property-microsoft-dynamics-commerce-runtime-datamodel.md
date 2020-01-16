---
title: SalesLine.UnitOfMeasureSymbol Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: UnitOfMeasureSymbol Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.UnitOfMeasureSymbol
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.unitofmeasuresymbol(v=AX.60)
ms:contentKeyID: 62211131
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.UnitOfMeasureSymbol
dev_langs:
- CSharp
- C++
- VB
---

# UnitOfMeasureSymbol Property

Gets or sets the sales unit of measure to be converted.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property UnitOfMeasureSymbol As String
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As String

value = instance.UnitOfMeasureSymbol

instance.UnitOfMeasureSymbol = value
```

``` csharp
[DataMemberAttribute]
public string UnitOfMeasureSymbol { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ UnitOfMeasureSymbol {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


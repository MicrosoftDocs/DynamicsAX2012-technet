---
title: ReasonCodeLine.LineTypeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LineTypeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeLine.LineTypeValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncodeline.linetypevalue(v=AX.60)
ms:contentKeyID: 62204551
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeLine.LineTypeValue
dev_langs:
- CSharp
- C++
- VB
---

# LineTypeValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the value of the ReasonCodeLineType enum. Used by OData only.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LineTypeValue As Integer
    Get
    Set
'Usage
Dim instance As ReasonCodeLine
Dim value As Integer

value = instance.LineTypeValue

instance.LineTypeValue = value
```

``` csharp
[DataMemberAttribute]
public int LineTypeValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int LineTypeValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[ReasonCodeLine Class](reasoncodeline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


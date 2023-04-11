---
title: NumberSequenceSeedData.DataTypeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DataTypeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.NumberSequenceSeedData.DataTypeValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.numbersequenceseeddata.datatypevalue(v=AX.60)
ms:contentKeyID: 65318806
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.NumberSequenceSeedData.DataTypeValue
dev_langs:
- CSharp
- C++
- VB
---

# DataTypeValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the value of number sequence seed data type. Used by OData only.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DataTypeValue As Integer
    Get
    Set
'Usage
Dim instance As NumberSequenceSeedData
Dim value As Integer

value = instance.DataTypeValue

instance.DataTypeValue = value
```

``` csharp
[DataMemberAttribute]
public int DataTypeValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int DataTypeValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[NumberSequenceSeedData Class](numbersequenceseeddata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


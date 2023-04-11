---
title: Shift.CustomerCount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CustomerCount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.CustomerCount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shift.customercount(v=AX.60)
ms:contentKeyID: 62209645
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.CustomerCount
dev_langs:
- CSharp
- C++
- VB
---

# CustomerCount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets count of customers visited.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CUSTOMERSCOUNT")> _
Public Property CustomerCount As Integer
    Get
    Set
'Usage
Dim instance As Shift
Dim value As Integer

value = instance.CustomerCount

instance.CustomerCount = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CUSTOMERSCOUNT")]
public int CustomerCount { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CUSTOMERSCOUNT")]
public:
property int CustomerCount {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[Shift Class](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


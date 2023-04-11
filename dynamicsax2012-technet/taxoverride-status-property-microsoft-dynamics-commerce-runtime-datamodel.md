---
title: TaxOverride.Status Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Status Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxOverride.Status
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.taxoverride.status(v=AX.60)
ms:contentKeyID: 62212837
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxOverride.Status
dev_langs:
- CSharp
- C++
- VB
---

# Status Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the status of the sales tax override.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("STATUS")> _
Public Property Status As Integer
    Get
    Set
'Usage
Dim instance As TaxOverride
Dim value As Integer

value = instance.Status

instance.Status = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("STATUS")]
public int Status { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"STATUS")]
public:
property int Status {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[TaxOverride Class](taxoverride-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


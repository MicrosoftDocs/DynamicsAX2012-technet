---
title: RetailDiscountLine.MixAndMatchLineGroup Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MixAndMatchLineGroup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscountLine.MixAndMatchLineGroup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.retaildiscountline.mixandmatchlinegroup(v=AX.60)
ms:contentKeyID: 62204549
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscountLine.MixAndMatchLineGroup
dev_langs:
- CSharp
- C++
- VB
---

# MixAndMatchLineGroup Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the line group for this rule if this is a mix and match discount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("LINEGROUP")> _
Public Property MixAndMatchLineGroup As String
    Get
    Set
'Usage
Dim instance As RetailDiscountLine
Dim value As String

value = instance.MixAndMatchLineGroup

instance.MixAndMatchLineGroup = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("LINEGROUP")]
public string MixAndMatchLineGroup { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"LINEGROUP")]
public:
property String^ MixAndMatchLineGroup {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[RetailDiscountLine Class](retaildiscountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


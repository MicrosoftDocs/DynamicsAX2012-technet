---
title: Affiliation.AffiliationType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AffiliationType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Affiliation.AffiliationType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.affiliation.affiliationtype(v=AX.60)
ms:contentKeyID: 62212295
author: tfehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Affiliation.AffiliationType
dev_langs:
- CSharp
- C++
- VB
---

# AffiliationType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the affiliation type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("AFFILIATIONTYPE")> _
<IgnoreDataMemberAttribute> _
Public Property AffiliationType As RetailAffiliationType
    Get
    Set
'Usage
Dim instance As Affiliation
Dim value As RetailAffiliationType

value = instance.AffiliationType

instance.AffiliationType = value
```

``` csharp
[ColumnAttribute("AFFILIATIONTYPE")]
[IgnoreDataMemberAttribute]
public RetailAffiliationType AffiliationType { get; set; }
```

``` c++
[ColumnAttribute(L"AFFILIATIONTYPE")]
[IgnoreDataMemberAttribute]
public:
property RetailAffiliationType AffiliationType {
    RetailAffiliationType get ();
    void set (RetailAffiliationType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailAffiliationType](retailaffiliationtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [RetailAffiliationType](retailaffiliationtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[Affiliation Class](affiliation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


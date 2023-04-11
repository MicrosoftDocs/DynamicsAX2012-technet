---
title: AffiliationLoyaltyTier.ReasonCodeLines Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReasonCodeLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.AffiliationLoyaltyTier.ReasonCodeLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.affiliationloyaltytier.reasoncodelines(v=AX.60)
ms:contentKeyID: 62208394
author: tonyafehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AffiliationLoyaltyTier.ReasonCodeLines
dev_langs:
- CSharp
- C++
- VB
---

# ReasonCodeLines Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the reason code lines.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ReasonCodeLines As Collection(Of ReasonCodeLine)
    Get
    Set
'Usage
Dim instance As AffiliationLoyaltyTier
Dim value As Collection(Of ReasonCodeLine)

value = instance.ReasonCodeLines

instance.ReasonCodeLines = value
```

``` csharp
[DataMemberAttribute]
public Collection<ReasonCodeLine> ReasonCodeLines { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<ReasonCodeLine^>^ ReasonCodeLines {
    Collection<ReasonCodeLine^>^ get ();
    void set (Collection<ReasonCodeLine^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[ReasonCodeLine](reasoncodeline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [Collection\<T\>](https://technet.microsoft.com/library/ms132397\(v=ax.60\)).  

## See Also

#### Reference

[AffiliationLoyaltyTier Class](affiliationloyaltytier-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


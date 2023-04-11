---
title: ListingPublishStatus.AppliedAction Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AppliedAction Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ListingPublishStatus.AppliedAction
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.listingpublishstatus.appliedaction(v=AX.60)
ms:contentKeyID: 49842176
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ListingPublishStatus.AppliedAction
dev_langs:
- CSharp
- C++
- VB
---

# AppliedAction Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the action for which status was captured.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("APPLIEDACTION")> _
Public Property AppliedAction As PublishingAction
    Get
    Set
'Usage
Dim instance As ListingPublishStatus
Dim value As PublishingAction

value = instance.AppliedAction

instance.AppliedAction = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("APPLIEDACTION")]
public PublishingAction AppliedAction { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"APPLIEDACTION")]
public:
property PublishingAction AppliedAction {
    PublishingAction get ();
    void set (PublishingAction value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PublishingAction](publishingaction-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [PublishingAction](publishingaction-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ListingPublishStatus Class](listingpublishstatus-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


---
title: ProductChangeTrackingInformation.RequestedAction Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RequestedAction Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingInformation.RequestedAction
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productchangetrackinginformation.requestedaction(v=AX.60)
ms:contentKeyID: 62215080
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingInformation.RequestedAction
dev_langs:
- CSharp
- C++
- VB
---

# RequestedAction Property

Gets the action requested by catalog publisher.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property RequestedAction As PublishingAction
    Get
    Private Set
'Usage
Dim instance As ProductChangeTrackingInformation
Dim value As PublishingAction

value = instance.RequestedAction
```

``` csharp
[IgnoreDataMemberAttribute]
public PublishingAction RequestedAction { get; private set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property PublishingAction RequestedAction {
    PublishingAction get ();
    private: void set (PublishingAction value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PublishingAction](publishingaction-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [PublishingAction](publishingaction-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ProductChangeTrackingInformation Class](productchangetrackinginformation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


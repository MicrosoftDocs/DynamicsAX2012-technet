---
title: GetIndependentProductPriceDiscountRequest.Context Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Context Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetIndependentProductPriceDiscountRequest.Context
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getindependentproductpricediscountrequest.context(v=AX.60)
ms:contentKeyID: 65322649
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetIndependentProductPriceDiscountRequest.Context
dev_langs:
- CSharp
- C++
- VB
---

# Context Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Context As ProjectionDomain
    Get
    Set
'Usage
Dim instance As GetIndependentProductPriceDiscountRequest
Dim value As ProjectionDomain

value = instance.Context

instance.Context = value
```

``` csharp
[DataMemberAttribute]
public ProjectionDomain Context { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property ProjectionDomain^ Context {
    ProjectionDomain^ get ();
    void set (ProjectionDomain^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProjectionDomain](projectiondomain-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetIndependentProductPriceDiscountRequest Class](getindependentproductpricediscountrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


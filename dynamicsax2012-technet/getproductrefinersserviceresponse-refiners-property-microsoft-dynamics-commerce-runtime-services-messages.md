---
title: GetProductRefinersServiceResponse.Refiners Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Refiners Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetProductRefinersServiceResponse.Refiners
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getproductrefinersserviceresponse.refiners(v=AX.60)
ms:contentKeyID: 65321967
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetProductRefinersServiceResponse.Refiners
dev_langs:
- CSharp
- C++
- VB
---

# Refiners Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<RequiredAttribute> _
<DataMemberAttribute> _
Public Property Refiners As ReadOnlyCollection(Of ProductRefiner)
    Get
    Private Set
'Usage
Dim instance As GetProductRefinersServiceResponse
Dim value As ReadOnlyCollection(Of ProductRefiner)

value = instance.Refiners
```

``` csharp
[RequiredAttribute]
[DataMemberAttribute]
public ReadOnlyCollection<ProductRefiner> Refiners { get; private set; }
```

``` c++
[RequiredAttribute]
[DataMemberAttribute]
public:
property ReadOnlyCollection<ProductRefiner^>^ Refiners {
    ReadOnlyCollection<ProductRefiner^>^ get ();
    private: void set (ReadOnlyCollection<ProductRefiner^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductRefiner](productrefiner-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetProductRefinersServiceResponse Class](getproductrefinersserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


---
title: TaxCode Constructor (RequestContext, TaxableItem, TaxCodeInterval) (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: TaxCode Constructor (RequestContext, TaxableItem, TaxCodeInterval)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.#ctor(Microsoft.Dynamics.Commerce.Runtime.RequestContext,Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableItem,Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxCodeInterval)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.taxcode.taxcode(v=AX.60)
ms:contentKeyID: 62207424
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# TaxCode Constructor (RequestContext, TaxableItem, TaxCodeInterval)

Initializes a new instance of the [TaxCode](taxcode-class-microsoft-dynamics-commerce-runtime-services.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    context As RequestContext, _
    lineItem As TaxableItem, _
    interval As TaxCodeInterval _
)
'Usage
Dim context As RequestContext
Dim lineItem As TaxableItem
Dim interval As TaxCodeInterval

Dim instance As New TaxCode(context, _
    lineItem, interval)
```

``` csharp
public TaxCode(
    RequestContext context,
    TaxableItem lineItem,
    TaxCodeInterval interval
)
```

``` c++
public:
TaxCode(
    RequestContext^ context, 
    TaxableItem^ lineItem, 
    TaxCodeInterval^ interval
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - lineItem  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableItem](taxableitem-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - interval  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxCodeInterval](taxcodeinterval-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[TaxCode Class](taxcode-class-microsoft-dynamics-commerce-runtime-services.md)

[TaxCode Overload](taxcode-constructor-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)


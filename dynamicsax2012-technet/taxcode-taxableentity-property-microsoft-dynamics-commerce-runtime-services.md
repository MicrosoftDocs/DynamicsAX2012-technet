---
title: TaxCode.TaxableEntity Property  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: TaxableEntity Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.TaxableEntity
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.taxcode.taxableentity(v=AX.60)
ms:contentKeyID: 49851774
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.TaxableEntity
dev_langs:
- CSharp
- C++
- VB
---

# TaxableEntity Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the taxable entity.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Property TaxableEntity As TaxableItem
    Get
    Protected Set
'Usage
Dim instance As TaxCode
Dim value As TaxableItem

value = instance.TaxableEntity

instance.TaxableEntity = value
```

``` csharp
public TaxableItem TaxableEntity { get; protected set; }
```

``` c++
public:
property TaxableItem^ TaxableEntity {
    TaxableItem^ get ();
    protected: void set (TaxableItem^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableItem](taxableitem-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The taxable entity.  

## See Also

#### Reference

[TaxCode Class](taxcode-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)


---
title: TaxCodeIndia.TaxType Property  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: TaxType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.TaxCodeIndia.TaxType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.taxcodeindia.taxtype(v=AX.60)
ms:contentKeyID: 62206356
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.TaxCodeIndia.TaxType
dev_langs:
- CSharp
- C++
- VB
---

# TaxType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the tax type of the code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Property TaxType As TaxTypeIndia
    Get
    Set
'Usage
Dim instance As TaxCodeIndia
Dim value As TaxTypeIndia

value = instance.TaxType

instance.TaxType = value
```

``` csharp
public TaxTypeIndia TaxType { get; set; }
```

``` c++
public:
property TaxTypeIndia TaxType {
    TaxTypeIndia get ();
    void set (TaxTypeIndia value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxTypeIndia](taxtypeindia-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [TaxTypeIndia](taxtypeindia-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[TaxCodeIndia Class](taxcodeindia-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)


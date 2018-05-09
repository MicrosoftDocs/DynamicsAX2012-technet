---
title: TaxCodeProvider.TaxCodePriority Method  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: TaxCodePriority Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.TaxCodeProvider.TaxCodePriority(Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.taxcodeprovider.taxcodepriority(v=AX.60)
ms:contentKeyID: 49849785
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.TaxCodeProvider.TaxCodePriority
dev_langs:
- CSharp
- C++
- VB
---

# TaxCodePriority Method

Gets the priority of the specified tax code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Protected Shared Function TaxCodePriority ( _
    code As TaxCode _
) As Integer
'Usage
Dim code As TaxCode
Dim returnValue As Integer

returnValue = TaxCodeProvider.TaxCodePriority(code)
```

``` csharp
protected static int TaxCodePriority(
    TaxCode code
)
```

``` c++
protected:
static int TaxCodePriority(
    TaxCode^ code
)
```

#### Parameters

  - code  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode](taxcode-class-microsoft-dynamics-commerce-runtime-services.md)  

#### Return Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
A value indicating the priority of the tax code.  

## See Also

#### Reference

[TaxCodeProvider Class](taxcodeprovider-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)


---
title: GetPriceServiceRequest.Validate Method  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Validate Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetPriceServiceRequest.Validate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getpriceservicerequest.validate(v=AX.60)
ms:contentKeyID: 65321005
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetPriceServiceRequest.Validate
dev_langs:
- CSharp
- C++
- VB
---

# Validate Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

This member overrides [Request.Validate()](request-validate-method-microsoft-dynamics-commerce-runtime-messages.md).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Overrides Function Validate As IEnumerable(Of DataValidationFailure)
'Usage
Dim instance As GetPriceServiceRequest
Dim returnValue As IEnumerable(Of DataValidationFailure)

returnValue = instance.Validate()
```

``` csharp
public override IEnumerable<DataValidationFailure> Validate()
```

``` c++
public:
virtual IEnumerable<DataValidationFailure^>^ Validate() override
```

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[DataValidationFailure](datavalidationfailure-class-microsoft-dynamics-commerce-runtime.md)\>  

## See Also

#### Reference

[GetPriceServiceRequest Class](getpriceservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


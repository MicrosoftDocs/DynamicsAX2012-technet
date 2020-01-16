---
title: CreateOrderFromCartRequest.Validate Method  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Validate Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.CreateOrderFromCartRequest.Validate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.createorderfromcartrequest.validate(v=AX.60)
ms:contentKeyID: 65320151
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.CreateOrderFromCartRequest.Validate
dev_langs:
- CSharp
- C++
- VB
---

# Validate Method

This member overrides [Request.Validate()](request-validate-method-microsoft-dynamics-commerce-runtime-messages.md).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Overrides Function Validate As IEnumerable(Of DataValidationFailure)
'Usage
Dim instance As CreateOrderFromCartRequest
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

[CreateOrderFromCartRequest Class](createorderfromcartrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


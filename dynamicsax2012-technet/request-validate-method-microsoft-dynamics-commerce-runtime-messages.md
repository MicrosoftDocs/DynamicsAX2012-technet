---
title: Request.Validate Method  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Validate Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.Request.Validate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.request.validate(v=AX.60)
ms:contentKeyID: 65315742
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.Request.Validate
dev_langs:
- CSharp
- C++
- VB
---

# Validate Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function Validate As IEnumerable(Of DataValidationFailure)
'Usage
Dim instance As Request
Dim returnValue As IEnumerable(Of DataValidationFailure)

returnValue = instance.Validate()
```

``` csharp
public virtual IEnumerable<DataValidationFailure> Validate()
```

``` c++
public:
virtual IEnumerable<DataValidationFailure^>^ Validate()
```

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[DataValidationFailure](datavalidationfailure-class-microsoft-dynamics-commerce-runtime.md)\>  

## See Also

#### Reference

[Request Class](request-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


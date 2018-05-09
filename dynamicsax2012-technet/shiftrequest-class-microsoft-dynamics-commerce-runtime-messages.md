---
title: ShiftRequest Class (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ShiftRequest Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Messages.ShiftRequest
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.shiftrequest(v=AX.60)
ms:contentKeyID: 62209532
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.ShiftRequest
dev_langs:
- CSharp
- C++
- VB
---

# ShiftRequest Class

Resume / Use shift request.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public MustInherit Class ShiftRequest _
    Inherits Request
'Usage
Dim instance As ShiftRequest
```

``` csharp
[DataContractAttribute]
public abstract class ShiftRequest : Request
```

``` c++
[DataContractAttribute]
public ref class ShiftRequest abstract : public Request
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Messages.Request](request-class-microsoft-dynamics-commerce-runtime-messages.md)  
    Microsoft.Dynamics.Commerce.Runtime.Messages.ShiftRequest  
      [Microsoft.Dynamics.Commerce.Runtime.Messages.ResumeShiftRequest](resumeshiftrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Messages.UseShiftRequest](useshiftrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


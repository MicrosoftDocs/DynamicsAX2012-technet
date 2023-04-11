---
title: ChangeShiftStatusResponse.Shift Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Shift Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.ChangeShiftStatusResponse.Shift
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.changeshiftstatusresponse.shift(v=AX.60)
ms:contentKeyID: 62211437
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.ChangeShiftStatusResponse.Shift
dev_langs:
- CSharp
- C++
- VB
---

# Shift Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the Shift.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Shift As Shift
    Get
    Private Set
'Usage
Dim instance As ChangeShiftStatusResponse
Dim value As Shift

value = instance.Shift
```

``` csharp
[DataMemberAttribute]
public Shift Shift { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Shift^ Shift {
    Shift^ get ();
    private: void set (Shift^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [Shift](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ChangeShiftStatusResponse Class](changeshiftstatusresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


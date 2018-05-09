---
title: CreateShiftRequest.CashDrawer Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: CashDrawer Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.CreateShiftRequest.CashDrawer
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.createshiftrequest.cashdrawer(v=AX.60)
ms:contentKeyID: 62214663
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.CreateShiftRequest.CashDrawer
dev_langs:
- CSharp
- C++
- VB
---

# CashDrawer Property

Gets or sets the cashdrawer.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CashDrawer As String
    Get
    Set
'Usage
Dim instance As CreateShiftRequest
Dim value As String

value = instance.CashDrawer

instance.CashDrawer = value
```

``` csharp
[DataMemberAttribute]
public string CashDrawer { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ CashDrawer {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The cashdrawer.  

## See Also

#### Reference

[CreateShiftRequest Class](createshiftrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


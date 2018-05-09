---
title: GetTillLayoutResponse.TillLayout Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: TillLayout Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetTillLayoutResponse.TillLayout
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.gettilllayoutresponse.tilllayout(v=AX.60)
ms:contentKeyID: 62209102
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetTillLayoutResponse.TillLayout
dev_langs:
- CSharp
- C++
- VB
---

# TillLayout Property

Gets the screen layout.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TillLayout As TillLayout
    Get
    Private Set
'Usage
Dim instance As GetTillLayoutResponse
Dim value As TillLayout

value = instance.TillLayout
```

``` csharp
[DataMemberAttribute]
public TillLayout TillLayout { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property TillLayout^ TillLayout {
    TillLayout^ get ();
    private: void set (TillLayout^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TillLayout](tilllayout-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [TillLayout](tilllayout-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetTillLayoutResponse Class](gettilllayoutresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


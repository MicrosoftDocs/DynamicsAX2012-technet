---
title: GetButtonGridByIdRequest.ButtonGridId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ButtonGridId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetButtonGridByIdRequest.ButtonGridId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getbuttongridbyidrequest.buttongridid(v=AX.60)
ms:contentKeyID: 62208114
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetButtonGridByIdRequest.ButtonGridId
dev_langs:
- CSharp
- C++
- VB
---

# ButtonGridId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the identifier of the buttongrid to retrieve.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ButtonGridId As String
    Get
    Private Set
'Usage
Dim instance As GetButtonGridByIdRequest
Dim value As String

value = instance.ButtonGridId
```

``` csharp
[DataMemberAttribute]
public string ButtonGridId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ButtonGridId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetButtonGridByIdRequest Class](getbuttongridbyidrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


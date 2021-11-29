---
title: SaveReasonCodeLineRequest Constructor (String, String, ReasonCodeLine) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: SaveReasonCodeLineRequest Constructor (String, String, ReasonCodeLine)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.SaveReasonCodeLineRequest.#ctor(System.String,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeLine)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.savereasoncodelinerequest.savereasoncodelinerequest(v=AX.60)
ms:contentKeyID: 62207861
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SaveReasonCodeLineRequest Constructor (String, String, ReasonCodeLine)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [SaveReasonCodeLineRequest](savereasoncodelinerequest-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    cartId As String, _
    customerAccountNumber As String, _
    reasonCodeLine As ReasonCodeLine _
)
'Usage
Dim cartId As String
Dim customerAccountNumber As String
Dim reasonCodeLine As ReasonCodeLine

Dim instance As New SaveReasonCodeLineRequest(cartId, _
    customerAccountNumber, reasonCodeLine)
```

``` csharp
public SaveReasonCodeLineRequest(
    string cartId,
    string customerAccountNumber,
    ReasonCodeLine reasonCodeLine
)
```

``` c++
public:
SaveReasonCodeLineRequest(
    String^ cartId, 
    String^ customerAccountNumber, 
    ReasonCodeLine^ reasonCodeLine
)
```

#### Parameters

  - cartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - customerAccountNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - reasonCodeLine  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeLine](reasoncodeline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[SaveReasonCodeLineRequest Class](savereasoncodelinerequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[SaveReasonCodeLineRequest Overload](savereasoncodelinerequest-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


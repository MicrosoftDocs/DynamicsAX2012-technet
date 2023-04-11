---
title: ValidateTenderLineForAddRequest Constructor (String, TenderLine) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ValidateTenderLineForAddRequest Constructor (String, TenderLine)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.ValidateTenderLineForAddRequest.#ctor(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLine)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.validatetenderlineforaddrequest.validatetenderlineforaddrequest(v=AX.60)
ms:contentKeyID: 65319619
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ValidateTenderLineForAddRequest Constructor (String, TenderLine)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    cartId As String, _
    tenderLine As TenderLine _
)
'Usage
Dim cartId As String
Dim tenderLine As TenderLine

Dim instance As New ValidateTenderLineForAddRequest(cartId, _
    tenderLine)
```

``` csharp
public ValidateTenderLineForAddRequest(
    string cartId,
    TenderLine tenderLine
)
```

``` c++
public:
ValidateTenderLineForAddRequest(
    String^ cartId, 
    TenderLine^ tenderLine
)
```

#### Parameters

  - cartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - tenderLine  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLine](tenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ValidateTenderLineForAddRequest Class](validatetenderlineforaddrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[ValidateTenderLineForAddRequest Overload](validatetenderlineforaddrequest-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


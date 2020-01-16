---
title: GetButtonGridByIdRequest Constructor (String, QueryResultSettings) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetButtonGridByIdRequest Constructor (String, QueryResultSettings)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetButtonGridByIdRequest.#ctor(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getbuttongridbyidrequest.getbuttongridbyidrequest(v=AX.60)
ms:contentKeyID: 65316372
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetButtonGridByIdRequest Constructor (String, QueryResultSettings)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    buttonGridId As String, _
    buttonGridButtonsSettings As QueryResultSettings _
)
'Usage
Dim buttonGridId As String
Dim buttonGridButtonsSettings As QueryResultSettings

Dim instance As New GetButtonGridByIdRequest(buttonGridId, _
    buttonGridButtonsSettings)
```

``` csharp
public GetButtonGridByIdRequest(
    string buttonGridId,
    QueryResultSettings buttonGridButtonsSettings
)
```

``` c++
public:
GetButtonGridByIdRequest(
    String^ buttonGridId, 
    QueryResultSettings^ buttonGridButtonsSettings
)
```

#### Parameters

  - buttonGridId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - buttonGridButtonsSettings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetButtonGridByIdRequest Class](getbuttongridbyidrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetButtonGridByIdRequest Overload](getbuttongridbyidrequest-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


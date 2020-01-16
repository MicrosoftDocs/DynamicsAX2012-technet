---
title: GetReasonCodesRequest Constructor (String, QueryResultSettings) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetReasonCodesRequest Constructor (String, QueryResultSettings)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetReasonCodesRequest.#ctor(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getreasoncodesrequest.getreasoncodesrequest(v=AX.60)
ms:contentKeyID: 65321683
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetReasonCodesRequest Constructor (String, QueryResultSettings)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    reasonCodeId As String, _
    settings As QueryResultSettings _
)
'Usage
Dim reasonCodeId As String
Dim settings As QueryResultSettings

Dim instance As New GetReasonCodesRequest(reasonCodeId, _
    settings)
```

``` csharp
public GetReasonCodesRequest(
    string reasonCodeId,
    QueryResultSettings settings
)
```

``` c++
public:
GetReasonCodesRequest(
    String^ reasonCodeId, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - reasonCodeId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetReasonCodesRequest Class](getreasoncodesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetReasonCodesRequest Overload](getreasoncodesrequest-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


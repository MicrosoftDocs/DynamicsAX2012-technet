---
title: GetButtonGridsByIdsRequest Constructor (IEnumerable(String), QueryResultSettings) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetButtonGridsByIdsRequest Constructor (IEnumerable(String), QueryResultSettings)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetButtonGridsByIdsRequest.#ctor(System.Collections.Generic.IEnumerable{System.String},Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getbuttongridsbyidsrequest.getbuttongridsbyidsrequest(v=AX.60)
ms:contentKeyID: 65318331
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetButtonGridsByIdsRequest Constructor (IEnumerable(String), QueryResultSettings)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    buttonGridIds As IEnumerable(Of String), _
    buttonGridSettings As QueryResultSettings _
)
'Usage
Dim buttonGridIds As IEnumerable(Of String)
Dim buttonGridSettings As QueryResultSettings

Dim instance As New GetButtonGridsByIdsRequest(buttonGridIds, _
    buttonGridSettings)
```

``` csharp
public GetButtonGridsByIdsRequest(
    IEnumerable<string> buttonGridIds,
    QueryResultSettings buttonGridSettings
)
```

``` c++
public:
GetButtonGridsByIdsRequest(
    IEnumerable<String^>^ buttonGridIds, 
    QueryResultSettings^ buttonGridSettings
)
```

#### Parameters

  - buttonGridIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - buttonGridSettings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetButtonGridsByIdsRequest Class](getbuttongridsbyidsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetButtonGridsByIdsRequest Overload](getbuttongridsbyidsrequest-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


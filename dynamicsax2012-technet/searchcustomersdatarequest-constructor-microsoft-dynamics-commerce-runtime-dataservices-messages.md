---
title: SearchCustomersDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: SearchCustomersDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SearchCustomersDataRequest.#ctor(System.String,System.Boolean,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.searchcustomersdatarequest.searchcustomersdatarequest(v=AX.60)
ms:contentKeyID: 65319101
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SearchCustomersDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# SearchCustomersDataRequest Constructor

Initializes a new instance of the [SearchCustomersDataRequest](searchcustomersdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    keyword As String, _
    onlyCurrentCompany As Boolean, _
    settings As QueryResultSettings _
)
'Usage
Dim keyword As String
Dim onlyCurrentCompany As Boolean
Dim settings As QueryResultSettings

Dim instance As New SearchCustomersDataRequest(keyword, _
    onlyCurrentCompany, settings)
```

``` csharp
public SearchCustomersDataRequest(
    string keyword,
    bool onlyCurrentCompany,
    QueryResultSettings settings
)
```

``` c++
public:
SearchCustomersDataRequest(
    String^ keyword, 
    bool onlyCurrentCompany, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - keyword  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - onlyCurrentCompany  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[SearchCustomersDataRequest Class](searchcustomersdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


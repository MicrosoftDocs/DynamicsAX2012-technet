---
title: GetSupportedReportsDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetSupportedReportsDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetSupportedReportsDataRequest.#ctor(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getsupportedreportsdatarequest.getsupportedreportsdatarequest(v=AX.60)
ms:contentKeyID: 65320463
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetSupportedReportsDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetSupportedReportsDataRequest Constructor

Initializes a new instance of the [GetSupportedReportsDataRequest](getsupportedreportsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    locale As String, _
    settings As QueryResultSettings _
)
'Usage
Dim locale As String
Dim settings As QueryResultSettings

Dim instance As New GetSupportedReportsDataRequest(locale, _
    settings)
```

``` csharp
public GetSupportedReportsDataRequest(
    string locale,
    QueryResultSettings settings
)
```

``` c++
public:
GetSupportedReportsDataRequest(
    String^ locale, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - locale  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetSupportedReportsDataRequest Class](getsupportedreportsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


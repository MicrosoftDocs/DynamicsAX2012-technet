---
title: GetEmployeeDataRequestBase Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetEmployeeDataRequestBase Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetEmployeeDataRequestBase.#ctor(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getemployeedatarequestbase.getemployeedatarequestbase(v=AX.60)
ms:contentKeyID: 65322949
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetEmployeeDataRequestBase.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetEmployeeDataRequestBase Constructor

Initializes a new instance of the [GetEmployeeDataRequestBase](getemployeedatarequestbase-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    staffId As String, _
    queryResultSettings As QueryResultSettings _
)
'Usage
Dim staffId As String
Dim queryResultSettings As QueryResultSettings

Dim instance As New GetEmployeeDataRequestBase(staffId, _
    queryResultSettings)
```

``` csharp
public GetEmployeeDataRequestBase(
    string staffId,
    QueryResultSettings queryResultSettings
)
```

``` c++
public:
GetEmployeeDataRequestBase(
    String^ staffId, 
    QueryResultSettings^ queryResultSettings
)
```

#### Parameters

  - staffId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - queryResultSettings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetEmployeeDataRequestBase Class](getemployeedatarequestbase-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


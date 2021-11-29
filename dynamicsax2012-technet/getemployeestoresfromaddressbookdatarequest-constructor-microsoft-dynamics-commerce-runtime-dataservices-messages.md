---
title: GetEmployeeStoresFromAddressBookDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetEmployeeStoresFromAddressBookDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetEmployeeStoresFromAddressBookDataRequest.#ctor(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getemployeestoresfromaddressbookdatarequest.getemployeestoresfromaddressbookdatarequest(v=AX.60)
ms:contentKeyID: 65321326
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetEmployeeStoresFromAddressBookDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetEmployeeStoresFromAddressBookDataRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetEmployeeStoresFromAddressBookDataRequest](getemployeestoresfromaddressbookdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    staffId As String, _
    settings As QueryResultSettings _
)
'Usage
Dim staffId As String
Dim settings As QueryResultSettings

Dim instance As New GetEmployeeStoresFromAddressBookDataRequest(staffId, _
    settings)
```

``` csharp
public GetEmployeeStoresFromAddressBookDataRequest(
    string staffId,
    QueryResultSettings settings
)
```

``` c++
public:
GetEmployeeStoresFromAddressBookDataRequest(
    String^ staffId, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - staffId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetEmployeeStoresFromAddressBookDataRequest Class](getemployeestoresfromaddressbookdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


---
title: GetEmployeeDataRequestBase.Settings Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: Settings Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetEmployeeDataRequestBase.Settings
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getemployeedatarequestbase.settings(v=AX.60)
ms:contentKeyID: 65323173
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetEmployeeDataRequestBase.Settings
dev_langs:
- CSharp
- C++
- VB
---

# Settings Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Settings As QueryResultSettings
    Get
    Private Set
'Usage
Dim instance As GetEmployeeDataRequestBase
Dim value As QueryResultSettings

value = instance.Settings
```

``` csharp
[DataMemberAttribute]
public QueryResultSettings Settings { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property QueryResultSettings^ Settings {
    QueryResultSettings^ get ();
    private: void set (QueryResultSettings^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetEmployeeDataRequestBase Class](getemployeedatarequestbase-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


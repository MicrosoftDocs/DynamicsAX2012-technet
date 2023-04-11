---
title: GetButtonGridsServiceRequest.ButtonGridQueryResultSettings Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ButtonGridQueryResultSettings Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetButtonGridsServiceRequest.ButtonGridQueryResultSettings
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getbuttongridsservicerequest.buttongridqueryresultsettings(v=AX.60)
ms:contentKeyID: 62207757
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetButtonGridsServiceRequest.ButtonGridQueryResultSettings
dev_langs:
- CSharp
- C++
- VB
---

# ButtonGridQueryResultSettings Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the buttongrid query result settings.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ButtonGridQueryResultSettings As QueryResultSettings
    Get
    Private Set
'Usage
Dim instance As GetButtonGridsServiceRequest
Dim value As QueryResultSettings

value = instance.ButtonGridQueryResultSettings
```

``` csharp
[DataMemberAttribute]
public QueryResultSettings ButtonGridQueryResultSettings { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property QueryResultSettings^ ButtonGridQueryResultSettings {
    QueryResultSettings^ get ();
    private: void set (QueryResultSettings^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns QueryResultSettings.  

## See Also

#### Reference

[GetButtonGridsServiceRequest Class](getbuttongridsservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


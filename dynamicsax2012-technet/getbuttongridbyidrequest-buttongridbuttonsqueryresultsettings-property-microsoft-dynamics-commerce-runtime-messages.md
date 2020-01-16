---
title: GetButtonGridByIdRequest.ButtonGridButtonsQueryResultSettings Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ButtonGridButtonsQueryResultSettings Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetButtonGridByIdRequest.ButtonGridButtonsQueryResultSettings
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getbuttongridbyidrequest.buttongridbuttonsqueryresultsettings(v=AX.60)
ms:contentKeyID: 62208329
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetButtonGridByIdRequest.ButtonGridButtonsQueryResultSettings
dev_langs:
- CSharp
- C++
- VB
---

# ButtonGridButtonsQueryResultSettings Property

Gets the buttongrid buttons query result settings.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ButtonGridButtonsQueryResultSettings As QueryResultSettings
    Get
    Private Set
'Usage
Dim instance As GetButtonGridByIdRequest
Dim value As QueryResultSettings

value = instance.ButtonGridButtonsQueryResultSettings
```

``` csharp
[DataMemberAttribute]
public QueryResultSettings ButtonGridButtonsQueryResultSettings { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property QueryResultSettings^ ButtonGridButtonsQueryResultSettings {
    QueryResultSettings^ get ();
    private: void set (QueryResultSettings^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns QueryResultSettings.  

## See Also

#### Reference

[GetButtonGridByIdRequest Class](getbuttongridbyidrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


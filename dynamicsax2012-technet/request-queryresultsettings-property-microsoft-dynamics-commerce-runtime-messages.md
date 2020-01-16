---
title: Request.QueryResultSettings Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: QueryResultSettings Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.Request.QueryResultSettings
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.request.queryresultsettings(v=AX.60)
ms:contentKeyID: 62212589
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.Request.QueryResultSettings
dev_langs:
- CSharp
- C++
- VB
---

# QueryResultSettings Property

Gets or sets the query result settings.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property QueryResultSettings As QueryResultSettings
    Get
    Set
'Usage
Dim instance As Request
Dim value As QueryResultSettings

value = instance.QueryResultSettings

instance.QueryResultSettings = value
```

``` csharp
[IgnoreDataMemberAttribute]
public QueryResultSettings QueryResultSettings { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property QueryResultSettings^ QueryResultSettings {
    QueryResultSettings^ get ();
    void set (QueryResultSettings^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns QueryResultSettings.  

## See Also

#### Reference

[Request Class](request-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


---
title: ReasonCodeSqlServerDataRequestHandler.SupportedRequestTypes Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices.ReasonCodes)
TOCTitle: SupportedRequestTypes Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices.ReasonCodes.ReasonCodeSqlServerDataRequestHandler.SupportedRequestTypes
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.sqlserver.dataservices.reasoncodes.reasoncodesqlserverdatarequesthandler.supportedrequesttypes(v=AX.60)
ms:contentKeyID: 65315830
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices.ReasonCodes.ReasonCodeSqlServerDataRequestHandler.SupportedRequestTypes
dev_langs:
- CSharp
- C++
- VB
---

# SupportedRequestTypes Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices.ReasonCodes](microsoft-dynamics-commerce-runtime-dataservices-sqlserver-dataservices-reasoncodes-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer (in Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property SupportedRequestTypes As IEnumerable(Of Type)
    Get
'Usage
Dim instance As ReasonCodeSqlServerDataRequestHandler
Dim value As IEnumerable(Of Type)

value = instance.SupportedRequestTypes
```

``` csharp
public IEnumerable<Type> SupportedRequestTypes { get; }
```

``` c++
public:
virtual property IEnumerable<Type^>^ SupportedRequestTypes {
    IEnumerable<Type^>^ get () sealed;
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Type](https://technet.microsoft.com/library/42892f65\(v=ax.60\))\>  

#### Implements

[IRequestHandler.SupportedRequestTypes](irequesthandler-supportedrequesttypes-property-microsoft-dynamics-commerce-runtime-workflow.md)  

## See Also

#### Reference

[ReasonCodeSqlServerDataRequestHandler Class](reasoncodesqlserverdatarequesthandler-class-microsoft-dynamics-commerce-runtime-dataservices-sqlserver-dataservices-reasoncodes.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices.ReasonCodes Namespace](microsoft-dynamics-commerce-runtime-dataservices-sqlserver-dataservices-reasoncodes-namespace.md)


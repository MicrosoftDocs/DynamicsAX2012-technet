---
title: UnitOfMeasureSqlServerDataRequestHandler.SupportedRequestTypes Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices)
TOCTitle: SupportedRequestTypes Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices.UnitOfMeasureSqlServerDataRequestHandler.SupportedRequestTypes
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.sqlserver.dataservices.unitofmeasuresqlserverdatarequesthandler.supportedrequesttypes(v=AX.60)
ms:contentKeyID: 65321743
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices.UnitOfMeasureSqlServerDataRequestHandler.SupportedRequestTypes
dev_langs:
- CSharp
- C++
- VB
---

# SupportedRequestTypes Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of supported request types by this handler.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices](microsoft-dynamics-commerce-runtime-dataservices-sqlserver-dataservices-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer (in Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property SupportedRequestTypes As IEnumerable(Of Type)
    Get
'Usage
Dim instance As UnitOfMeasureSqlServerDataRequestHandler
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
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

#### Implements

[IRequestHandler.SupportedRequestTypes](irequesthandler-supportedrequesttypes-property-microsoft-dynamics-commerce-runtime-workflow.md)  

## See Also

#### Reference

[UnitOfMeasureSqlServerDataRequestHandler Class](unitofmeasuresqlserverdatarequesthandler-class-microsoft-dynamics-commerce-runtime-dataservices-sqlserver-dataservices.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices Namespace](microsoft-dynamics-commerce-runtime-dataservices-sqlserver-dataservices-namespace.md)


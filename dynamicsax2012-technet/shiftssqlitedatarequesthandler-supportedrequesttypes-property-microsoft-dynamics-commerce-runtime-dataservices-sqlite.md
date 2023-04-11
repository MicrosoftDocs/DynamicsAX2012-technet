---
title: ShiftsSqliteDataRequestHandler.SupportedRequestTypes Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite)
TOCTitle: SupportedRequestTypes Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.ShiftsSqliteDataRequestHandler.SupportedRequestTypes
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.sqlite.shiftssqlitedatarequesthandler.supportedrequesttypes(v=AX.60)
ms:contentKeyID: 65322774
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.ShiftsSqliteDataRequestHandler.SupportedRequestTypes
dev_langs:
- CSharp
- C++
- VB
---

# SupportedRequestTypes Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite](microsoft-dynamics-commerce-runtime-dataservices-sqlite-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property SupportedRequestTypes As IEnumerable(Of Type)
    Get
'Usage
Dim instance As ShiftsSqliteDataRequestHandler
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

[ShiftsSqliteDataRequestHandler Class](shiftssqlitedatarequesthandler-class-microsoft-dynamics-commerce-runtime-dataservices-sqlite.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite Namespace](microsoft-dynamics-commerce-runtime-dataservices-sqlite-namespace.md)


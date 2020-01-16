---
title: RequestContextExtensions.GetSalesTransaction Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: GetSalesTransaction Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.RequestContextExtensions.GetSalesTransaction(Microsoft.Dynamics.Commerce.Runtime.RequestContext)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.requestcontextextensions.getsalestransaction(v=AX.60)
ms:contentKeyID: 65316280
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.RequestContextExtensions.GetSalesTransaction
dev_langs:
- CSharp
- C++
- VB
---

# GetSalesTransaction Method

Gets the sales transaction object from [RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Function GetSalesTransaction ( _
    requestContext As RequestContext _
) As SalesTransaction
'Usage
Dim requestContext As RequestContext
Dim returnValue As SalesTransaction

returnValue = requestContext.GetSalesTransaction()
```

``` csharp
public static SalesTransaction GetSalesTransaction(
    this RequestContext requestContext
)
```

``` c++
[ExtensionAttribute]
public:
static SalesTransaction^ GetSalesTransaction(
    RequestContext^ requestContext
)
```

#### Parameters

  - requestContext  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Instance of [SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md) from the parameter cache.  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[RequestContextExtensions Class](requestcontextextensions-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)


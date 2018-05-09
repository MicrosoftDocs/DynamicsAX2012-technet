---
title: SalesTransactionExtensions.ValidateSalesOrder Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: ValidateSalesOrder Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.SalesTransactionExtensions.ValidateSalesOrder(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction,Microsoft.Dynamics.Commerce.Runtime.RequestContext)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.salestransactionextensions.validatesalesorder(v=AX.60)
ms:contentKeyID: 65317185
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.SalesTransactionExtensions.ValidateSalesOrder
dev_langs:
- CSharp
- C++
- VB
---

# ValidateSalesOrder Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Sub ValidateSalesOrder ( _
    transaction As SalesTransaction, _
    context As RequestContext _
)
'Usage
Dim transaction As SalesTransaction
Dim context As RequestContext

transaction.ValidateSalesOrder(context)
```

``` csharp
public static void ValidateSalesOrder(
    this SalesTransaction transaction,
    RequestContext context
)
```

``` c++
[ExtensionAttribute]
public:
static void ValidateSalesOrder(
    SalesTransaction^ transaction, 
    RequestContext^ context
)
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[SalesTransactionExtensions Class](salestransactionextensions-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)


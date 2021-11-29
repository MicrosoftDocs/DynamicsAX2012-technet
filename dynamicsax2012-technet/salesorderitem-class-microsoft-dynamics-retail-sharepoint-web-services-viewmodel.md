---
title: SalesOrderItem Class (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: SalesOrderItem Class
ms:assetid: T:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SalesOrderItem
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.salesorderitem(v=AX.60)
ms:contentKeyID: 62204079
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SalesOrderItem
dev_langs:
- CSharp
- C++
- VB
---

# SalesOrderItem Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The sales order item view model representation.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<SerializableAttribute> _
<DataContractAttribute> _
Public NotInheritable Class SalesOrderItem _
    Inherits TransactionItem
'Usage
Dim instance As SalesOrderItem
```

``` csharp
[SerializableAttribute]
[DataContractAttribute]
public sealed class SalesOrderItem : TransactionItem
```

``` c++
[SerializableAttribute]
[DataContractAttribute]
public ref class SalesOrderItem sealed : public TransactionItem
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.TransactionItem](transactionitem-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
    Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SalesOrderItem  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)


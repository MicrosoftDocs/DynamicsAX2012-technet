---
title: ServiceHelper.ToCurrencyString Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel)
TOCTitle: ToCurrencyString Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel.ServiceHelper.ToCurrencyString(System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.objectmodel.servicehelper.tocurrencystring(v=AX.60)
ms:contentKeyID: 62205285
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel.ServiceHelper.ToCurrencyString
dev_langs:
- CSharp
- C++
- VB
---

# ToCurrencyString Method

Formats decimal value to represent currency.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel](microsoft-dynamics-retail-sharepoint-web-services-objectmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Function ToCurrencyString ( _
    amount As Decimal _
) As String
'Usage
Dim amount As Decimal
Dim returnValue As String

returnValue = amount.ToCurrencyString()
```

``` csharp
public static string ToCurrencyString(
    this decimal amount
)
```

``` c++
[ExtensionAttribute]
public:
static String^ ToCurrencyString(
    Decimal amount
)
```

#### Parameters

  - amount  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Amount as a currency string.  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[ServiceHelper Class](servicehelper-class-microsoft-dynamics-retail-sharepoint-web-services-objectmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-objectmodel-namespace.md)


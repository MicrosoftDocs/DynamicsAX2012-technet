---
title: TenderDataLine.LoyaltyCardId Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: LoyaltyCardId Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.TenderDataLine.LoyaltyCardId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.tenderdataline.loyaltycardid(v=AX.60)
ms:contentKeyID: 62206511
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.TenderDataLine.LoyaltyCardId
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyCardId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the loyalty card identifier.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LoyaltyCardId As String
    Get
    Set
'Usage
Dim instance As TenderDataLine
Dim value As String

value = instance.LoyaltyCardId

instance.LoyaltyCardId = value
```

``` csharp
[DataMemberAttribute]
public string LoyaltyCardId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ LoyaltyCardId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TenderDataLine Class](tenderdataline-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)


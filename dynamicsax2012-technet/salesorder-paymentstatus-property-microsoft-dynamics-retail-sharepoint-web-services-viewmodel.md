---
title: SalesOrder.PaymentStatus Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: PaymentStatus Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SalesOrder.PaymentStatus
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.salesorder.paymentstatus(v=AX.60)
ms:contentKeyID: 62207148
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SalesOrder.PaymentStatus
dev_langs:
- CSharp
- C++
- VB
---

# PaymentStatus Property

Gets or sets the payment status.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PaymentStatus As Integer
    Get
    Set
'Usage
Dim instance As SalesOrder
Dim value As Integer

value = instance.PaymentStatus

instance.PaymentStatus = value
```

``` csharp
[DataMemberAttribute]
public int PaymentStatus { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int PaymentStatus {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[SalesOrder Class](salesorder-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)


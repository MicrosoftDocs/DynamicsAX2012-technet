---
title: CreateSalesOrderResponse.OrderNumber Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: OrderNumber Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.CreateSalesOrderResponse.OrderNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.createsalesorderresponse.ordernumber(v=AX.60)
ms:contentKeyID: 65316318
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.CreateSalesOrderResponse.OrderNumber
dev_langs:
- CSharp
- C++
- VB
---

# OrderNumber Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property OrderNumber As String
    Get
    Set
'Usage
Dim instance As CreateSalesOrderResponse
Dim value As String

value = instance.OrderNumber

instance.OrderNumber = value
```

``` csharp
[DataMemberAttribute]
public string OrderNumber { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ OrderNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[CreateSalesOrderResponse Class](createsalesorderresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)


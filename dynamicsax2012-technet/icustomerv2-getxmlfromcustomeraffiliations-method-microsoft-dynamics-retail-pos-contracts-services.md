---
title: ICustomerV2.GetXmlFromCustomerAffiliations Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: GetXmlFromCustomerAffiliations Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICustomerV2.GetXmlFromCustomerAffiliations(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomer)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.icustomerv2.getxmlfromcustomeraffiliations(v=AX.60)
ms:contentKeyID: 62202336
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICustomerV2.GetXmlFromCustomerAffiliations
dev_langs:
- CSharp
- C++
- VB
---

# GetXmlFromCustomerAffiliations Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Get xml string from customer affiliations which would be transfered to transaction service.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function GetXmlFromCustomerAffiliations ( _
    customer As ICustomer _
) As String
'Usage
Dim instance As ICustomerV2
Dim customer As ICustomer
Dim returnValue As String

returnValue = instance.GetXmlFromCustomerAffiliations(customer)
```

``` csharp
string GetXmlFromCustomerAffiliations(
    ICustomer customer
)
```

``` c++
String^ GetXmlFromCustomerAffiliations(
    ICustomer^ customer
)
```

#### Parameters

  - customer  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomer](icustomer-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
An xml string.  

## See Also

#### Reference

[ICustomerV2 Interface](icustomerv2-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)


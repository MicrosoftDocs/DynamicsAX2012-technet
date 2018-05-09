---
title: ICustomerV2.SetCustomerAffiliationsFromXmL Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: SetCustomerAffiliationsFromXmL Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICustomerV2.SetCustomerAffiliationsFromXmL(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomer,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.icustomerv2.setcustomeraffiliationsfromxml(v=AX.60)
ms:contentKeyID: 62202042
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICustomerV2.SetCustomerAffiliationsFromXmL
dev_langs:
- CSharp
- C++
- VB
---

# SetCustomerAffiliationsFromXmL Method

Set affiliations for customers for customer from a xml got from transaction service.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub SetCustomerAffiliationsFromXmL ( _
    customer As ICustomer, _
    xml As String _
)
'Usage
Dim instance As ICustomerV2
Dim customer As ICustomer
Dim xml As String

instance.SetCustomerAffiliationsFromXmL(customer, _
    xml)
```

``` csharp
void SetCustomerAffiliationsFromXmL(
    ICustomer customer,
    string xml
)
```

``` c++
void SetCustomerAffiliationsFromXmL(
    ICustomer^ customer, 
    String^ xml
)
```

#### Parameters

  - customer  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomer](icustomer-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - xml  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ICustomerV2 Interface](icustomerv2-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)


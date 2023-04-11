---
title: ICustomerV2.SetAddressBookDataFromXml Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: SetAddressBookDataFromXml Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICustomerV2.SetAddressBookDataFromXml(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomer,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.icustomerv2.setaddressbookdatafromxml(v=AX.60)
ms:contentKeyID: 62205429
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICustomerV2.SetAddressBookDataFromXml
dev_langs:
- CSharp
- C++
- VB
---

# SetAddressBookDataFromXml Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Sets the address book data from XML returned by treansaction service.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub SetAddressBookDataFromXml ( _
    customer As ICustomer, _
    addressBookPartyXml As String _
)
'Usage
Dim instance As ICustomerV2
Dim customer As ICustomer
Dim addressBookPartyXml As String

instance.SetAddressBookDataFromXml(customer, _
    addressBookPartyXml)
```

``` csharp
void SetAddressBookDataFromXml(
    ICustomer customer,
    string addressBookPartyXml
)
```

``` c++
void SetAddressBookDataFromXml(
    ICustomer^ customer, 
    String^ addressBookPartyXml
)
```

#### Parameters

  - customer  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomer](icustomer-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - addressBookPartyXml  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ICustomerV2 Interface](icustomerv2-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)


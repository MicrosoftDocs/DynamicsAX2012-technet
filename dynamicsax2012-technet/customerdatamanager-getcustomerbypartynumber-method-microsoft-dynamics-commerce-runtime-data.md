---
title: CustomerDataManager.GetCustomerByPartyNumber Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetCustomerByPartyNumber Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.CustomerDataManager.GetCustomerByPartyNumber(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.customerdatamanager.getcustomerbypartynumber(v=AX.60)
ms:contentKeyID: 62208860
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.CustomerDataManager.GetCustomerByPartyNumber
dev_langs:
- CSharp
- C++
- VB
---

# GetCustomerByPartyNumber Method

Gets the customer by party number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetCustomerByPartyNumber ( _
    partyNumber As String _
) As Customer
'Usage
Dim instance As CustomerDataManager
Dim partyNumber As String
Dim returnValue As Customer

returnValue = instance.GetCustomerByPartyNumber(partyNumber)
```

``` csharp
public Customer GetCustomerByPartyNumber(
    string partyNumber
)
```

``` c++
public:
Customer^ GetCustomerByPartyNumber(
    String^ partyNumber
)
```

#### Parameters

  - partyNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The customer.  

## See Also

#### Reference

[CustomerDataManager Class](customerdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


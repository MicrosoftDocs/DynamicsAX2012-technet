---
title: CustomerDataManager.GetCustomerByRecordId Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetCustomerByRecordId Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.CustomerDataManager.GetCustomerByRecordId(System.Int64)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.customerdatamanager.getcustomerbyrecordid(v=AX.60)
ms:contentKeyID: 62204792
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.CustomerDataManager.GetCustomerByRecordId
dev_langs:
- CSharp
- C++
- VB
---

# GetCustomerByRecordId Method

Gets the customer by acccount number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetCustomerByRecordId ( _
    recordId As Long _
) As Customer
'Usage
Dim instance As CustomerDataManager
Dim recordId As Long
Dim returnValue As Customer

returnValue = instance.GetCustomerByRecordId(recordId)
```

``` csharp
public Customer GetCustomerByRecordId(
    long recordId
)
```

``` c++
public:
Customer^ GetCustomerByRecordId(
    long long recordId
)
```

#### Parameters

  - recordId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The customer.  

## See Also

#### Reference

[CustomerDataManager Class](customerdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


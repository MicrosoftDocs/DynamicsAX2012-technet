---
title: CustomerDataManager.GetInitializedCustomerFromGlobalCustomer Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetInitializedCustomerFromGlobalCustomer Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.CustomerDataManager.GetInitializedCustomerFromGlobalCustomer(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.customerdatamanager.getinitializedcustomerfromglobalcustomer(v=AX.60)
ms:contentKeyID: 62204568
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.CustomerDataManager.GetInitializedCustomerFromGlobalCustomer
dev_langs:
- CSharp
- C++
- VB
---

# GetInitializedCustomerFromGlobalCustomer Method

Gets an empty customer initialized with party information.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetInitializedCustomerFromGlobalCustomer ( _
    partyNumber As String _
) As Customer
'Usage
Dim instance As CustomerDataManager
Dim partyNumber As String
Dim returnValue As Customer

returnValue = instance.GetInitializedCustomerFromGlobalCustomer(partyNumber)
```

``` csharp
public Customer GetInitializedCustomerFromGlobalCustomer(
    string partyNumber
)
```

``` c++
public:
Customer^ GetInitializedCustomerFromGlobalCustomer(
    String^ partyNumber
)
```

#### Parameters

  - partyNumber  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
An empty customer.  

## See Also

#### Reference

[CustomerDataManager Class](customerdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


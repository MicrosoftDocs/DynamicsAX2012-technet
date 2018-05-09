---
title: CustomerDataManager.GetAddresses Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetAddresses Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.CustomerDataManager.GetAddresses(System.Collections.Generic.IEnumerable{System.Int64})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.customerdatamanager.getaddresses(v=AX.60)
ms:contentKeyID: 62209150
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.CustomerDataManager.GetAddresses
dev_langs:
- CSharp
- C++
- VB
---

# GetAddresses Method

Gets all addresses that meets the supplied criteria.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetAddresses ( _
    addressRecordIds As IEnumerable(Of Long) _
) As IEnumerable(Of Address)
'Usage
Dim instance As CustomerDataManager
Dim addressRecordIds As IEnumerable(Of Long)
Dim returnValue As IEnumerable(Of Address)

returnValue = instance.GetAddresses(addressRecordIds)
```

``` csharp
public IEnumerable<Address> GetAddresses(
    IEnumerable<long> addressRecordIds
)
```

``` c++
public:
IEnumerable<Address^>^ GetAddresses(
    IEnumerable<long long>^ addressRecordIds
)
```

#### Parameters

  - addressRecordIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[Address](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
A collection of customer address or empty list.  

## See Also

#### Reference

[CustomerDataManager Class](customerdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


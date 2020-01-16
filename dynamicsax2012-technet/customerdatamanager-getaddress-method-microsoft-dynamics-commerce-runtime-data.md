---
title: CustomerDataManager.GetAddress Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetAddress Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.CustomerDataManager.GetAddress(System.Int64,System.Nullable{System.Int64},Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.customerdatamanager.getaddress(v=AX.60)
ms:contentKeyID: 65320519
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.CustomerDataManager.GetAddress
dev_langs:
- CSharp
- C++
- VB
---

# GetAddress Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetAddress ( _
    addressRecordId As Long, _
    customerRecordId As Nullable(Of Long), _
    columnSet As ColumnSet _
) As Address
'Usage
Dim instance As CustomerDataManager
Dim addressRecordId As Long
Dim customerRecordId As Nullable(Of Long)
Dim columnSet As ColumnSet
Dim returnValue As Address

returnValue = instance.GetAddress(addressRecordId, _
    customerRecordId, columnSet)
```

``` csharp
public Address GetAddress(
    long addressRecordId,
    Nullable<long> customerRecordId,
    ColumnSet columnSet
)
```

``` c++
public:
Address^ GetAddress(
    long long addressRecordId, 
    Nullable<long long> customerRecordId, 
    ColumnSet^ columnSet
)
```

#### Parameters

  - addressRecordId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - customerRecordId  
    Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - columnSet  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Address](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[CustomerDataManager Class](customerdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


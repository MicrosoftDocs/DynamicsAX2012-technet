---
title: OrderManager.GetCartsByCustomer Method (String, Boolean, CalculationModes) (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetCartsByCustomer Method (String, Boolean, CalculationModes)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetCartsByCustomer(System.String,System.Boolean,Microsoft.Dynamics.Commerce.Runtime.DataModel.CalculationModes)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.ordermanager.getcartsbycustomer(v=AX.60)
ms:contentKeyID: 65320083
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetCartsByCustomer Method (String, Boolean, CalculationModes)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetCartsByCustomer ( _
    customerAccountNumber As String, _
    isActive As Boolean, _
    modes As CalculationModes _
) As ReadOnlyCollection(Of Cart)
'Usage
Dim instance As OrderManager
Dim customerAccountNumber As String
Dim isActive As Boolean
Dim modes As CalculationModes
Dim returnValue As ReadOnlyCollection(Of Cart)

returnValue = instance.GetCartsByCustomer(customerAccountNumber, _
    isActive, modes)
```

``` csharp
public ReadOnlyCollection<Cart> GetCartsByCustomer(
    string customerAccountNumber,
    bool isActive,
    CalculationModes modes
)
```

``` c++
public:
ReadOnlyCollection<Cart^>^ GetCartsByCustomer(
    String^ customerAccountNumber, 
    bool isActive, 
    CalculationModes modes
)
```

#### Parameters

  - customerAccountNumber  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - isActive  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - modes  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CalculationModes](calculationmodes-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[GetCartsByCustomer Overload](ordermanager-getcartsbycustomer-method-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)


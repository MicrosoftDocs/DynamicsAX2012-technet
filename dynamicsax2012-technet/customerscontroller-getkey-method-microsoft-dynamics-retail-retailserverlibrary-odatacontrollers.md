---
title: CustomersController.GetKey Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetKey Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CustomersController.GetKey(Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.customerscontroller.getkey(v=AX.60)
ms:contentKeyID: 62203454
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CustomersController.GetKey
dev_langs:
- CSharp
- C++
- VB
---

# GetKey Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the Customer key.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function GetKey ( _
    entity As Customer _
) As String
'Usage
Dim entity As Customer
Dim returnValue As String

returnValue = Me.GetKey(entity)
```

``` csharp
protected override string GetKey(
    Customer entity
)
```

``` c++
protected:
virtual String^ GetKey(
    Customer^ entity
) override
```

#### Parameters

  - entity  
    Type: Customer  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The key.  

## See Also

#### Reference

[CustomersController Class](customerscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)


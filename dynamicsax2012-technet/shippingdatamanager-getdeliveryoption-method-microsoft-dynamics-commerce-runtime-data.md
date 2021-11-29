---
title: ShippingDataManager.GetDeliveryOption Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetDeliveryOption Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ShippingDataManager.GetDeliveryOption(System.String,Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.shippingdatamanager.getdeliveryoption(v=AX.60)
ms:contentKeyID: 49834800
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ShippingDataManager.GetDeliveryOption
dev_langs:
- CSharp
- C++
- VB
---

# GetDeliveryOption Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

This method retrieves delivery mode option matching the given code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetDeliveryOption ( _
    code As String, _
    columns As ColumnSet _
) As DeliveryOption
'Usage
Dim instance As ShippingDataManager
Dim code As String
Dim columns As ColumnSet
Dim returnValue As DeliveryOption

returnValue = instance.GetDeliveryOption(code, _
    columns)
```

``` csharp
public DeliveryOption GetDeliveryOption(
    string code,
    ColumnSet columns
)
```

``` c++
public:
DeliveryOption^ GetDeliveryOption(
    String^ code, 
    ColumnSet^ columns
)
```

#### Parameters

  - code  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DeliveryOption](deliveryoption-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The delivery option.  

## See Also

#### Reference

[ShippingDataManager Class](shippingdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


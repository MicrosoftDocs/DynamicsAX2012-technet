---
title: ShippingDataManager.GetShippingAdapterConfiguration Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetShippingAdapterConfiguration Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ShippingDataManager.GetShippingAdapterConfiguration(System.Collections.Generic.IEnumerable{System.String},Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.shippingdatamanager.getshippingadapterconfiguration(v=AX.60)
ms:contentKeyID: 49824814
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ShippingDataManager.GetShippingAdapterConfiguration
dev_langs:
- CSharp
- C++
- VB
---

# GetShippingAdapterConfiguration Method

Gets the shipping adapter configuration based on delivery mode identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetShippingAdapterConfiguration ( _
    deliveryModeIds As IEnumerable(Of String), _
    columns As ColumnSet _
) As ReadOnlyCollection(Of ShippingAdapterConfig)
'Usage
Dim instance As ShippingDataManager
Dim deliveryModeIds As IEnumerable(Of String)
Dim columns As ColumnSet
Dim returnValue As ReadOnlyCollection(Of ShippingAdapterConfig)

returnValue = instance.GetShippingAdapterConfiguration(deliveryModeIds, _
    columns)
```

``` csharp
public ReadOnlyCollection<ShippingAdapterConfig> GetShippingAdapterConfiguration(
    IEnumerable<string> deliveryModeIds,
    ColumnSet columns
)
```

``` c++
public:
ReadOnlyCollection<ShippingAdapterConfig^>^ GetShippingAdapterConfiguration(
    IEnumerable<String^>^ deliveryModeIds, 
    ColumnSet^ columns
)
```

#### Parameters

  - deliveryModeIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[ShippingAdapterConfig](shippingadapterconfig-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Shipping adapter config records for all the requested delivery mode identifiers.  

## See Also

#### Reference

[ShippingDataManager Class](shippingdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


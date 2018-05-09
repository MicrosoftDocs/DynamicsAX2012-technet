---
title: ShippingDataManager.GetLineDeliveryPreferences Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetLineDeliveryPreferences Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ShippingDataManager.GetLineDeliveryPreferences(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.shippingdatamanager.getlinedeliverypreferences(v=AX.60)
ms:contentKeyID: 65322968
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ShippingDataManager.GetLineDeliveryPreferences
dev_langs:
- CSharp
- C++
- VB
---

# GetLineDeliveryPreferences Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetLineDeliveryPreferences ( _
    salesLines As IEnumerable(Of SalesLine) _
) As ReadOnlyCollection(Of LineDeliveryPreference)
'Usage
Dim instance As ShippingDataManager
Dim salesLines As IEnumerable(Of SalesLine)
Dim returnValue As ReadOnlyCollection(Of LineDeliveryPreference)

returnValue = instance.GetLineDeliveryPreferences(salesLines)
```

``` csharp
public ReadOnlyCollection<LineDeliveryPreference> GetLineDeliveryPreferences(
    IEnumerable<SalesLine> salesLines
)
```

``` c++
public:
ReadOnlyCollection<LineDeliveryPreference^>^ GetLineDeliveryPreferences(
    IEnumerable<SalesLine^>^ salesLines
)
```

#### Parameters

  - salesLines  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[LineDeliveryPreference](linedeliverypreference-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ShippingDataManager Class](shippingdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


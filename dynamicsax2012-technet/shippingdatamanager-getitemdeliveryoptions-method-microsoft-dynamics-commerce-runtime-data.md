---
title: ShippingDataManager.GetItemDeliveryOptions Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetItemDeliveryOptions Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ShippingDataManager.GetItemDeliveryOptions(System.String,System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.shippingdatamanager.getitemdeliveryoptions(v=AX.60)
ms:contentKeyID: 49832374
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ShippingDataManager.GetItemDeliveryOptions
dev_langs:
- CSharp
- C++
- VB
---

# GetItemDeliveryOptions Method

Gets the delivery options.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetItemDeliveryOptions ( _
    itemId As String, _
    variantInventDimId As String, _
    countryRegionId As String, _
    stateId As String _
) As ReadOnlyCollection(Of DeliveryOption)
'Usage
Dim instance As ShippingDataManager
Dim itemId As String
Dim variantInventDimId As String
Dim countryRegionId As String
Dim stateId As String
Dim returnValue As ReadOnlyCollection(Of DeliveryOption)

returnValue = instance.GetItemDeliveryOptions(itemId, _
    variantInventDimId, countryRegionId, _
    stateId)
```

``` csharp
public ReadOnlyCollection<DeliveryOption> GetItemDeliveryOptions(
    string itemId,
    string variantInventDimId,
    string countryRegionId,
    string stateId
)
```

``` c++
public:
ReadOnlyCollection<DeliveryOption^>^ GetItemDeliveryOptions(
    String^ itemId, 
    String^ variantInventDimId, 
    String^ countryRegionId, 
    String^ stateId
)
```

#### Parameters

  - itemId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - variantInventDimId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - countryRegionId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - stateId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[DeliveryOption](deliveryoption-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Matching delivery options.  

## See Also

#### Reference

[ShippingDataManager Class](shippingdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


---
title: InventoryManager.GetProductAvailabilities Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetProductAvailabilities Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.GetProductAvailabilities(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,System.Collections.Generic.IEnumerable{System.Int64},System.Int64,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.inventorymanager.getproductavailabilities(v=AX.60)
ms:contentKeyID: 65322183
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.GetProductAvailabilities
dev_langs:
- CSharp
- C++
- VB
---

# GetProductAvailabilities Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetProductAvailabilities ( _
    settings As QueryResultSettings, _
    productIds As IEnumerable(Of Long), _
    channelId As Long, _
    customerAccountNumber As String _
) As ReadOnlyCollection(Of ProductAvailableQuantity)
'Usage
Dim instance As InventoryManager
Dim settings As QueryResultSettings
Dim productIds As IEnumerable(Of Long)
Dim channelId As Long
Dim customerAccountNumber As String
Dim returnValue As ReadOnlyCollection(Of ProductAvailableQuantity)

returnValue = instance.GetProductAvailabilities(settings, _
    productIds, channelId, customerAccountNumber)
```

``` csharp
public ReadOnlyCollection<ProductAvailableQuantity> GetProductAvailabilities(
    QueryResultSettings settings,
    IEnumerable<long> productIds,
    long channelId,
    string customerAccountNumber
)
```

``` c++
public:
ReadOnlyCollection<ProductAvailableQuantity^>^ GetProductAvailabilities(
    QueryResultSettings^ settings, 
    IEnumerable<long long>^ productIds, 
    long long channelId, 
    String^ customerAccountNumber
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - productIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - customerAccountNumber  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[ProductAvailableQuantity](productavailablequantity-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[InventoryManager Class](inventorymanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)


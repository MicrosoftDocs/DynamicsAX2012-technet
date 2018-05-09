---
title: InventoryManager.GetItemPrice Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetItemPrice Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.GetItemPrice(System.String,System.String,System.String,System.String,System.String,System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.inventorymanager.getitemprice(v=AX.60)
ms:contentKeyID: 62214110
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.GetItemPrice
dev_langs:
- CSharp
- C++
- VB
---

# GetItemPrice Method

Gets the price of an item in context of the current customer.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetItemPrice ( _
    itemId As String, _
    inventoryDimensionId As String, _
    barcode As String, _
    customerAccountNumber As String, _
    unitOfMeasureSymbol As String, _
    quantity As Decimal _
) As ReadOnlyCollection(Of ProductPrice)
'Usage
Dim instance As InventoryManager
Dim itemId As String
Dim inventoryDimensionId As String
Dim barcode As String
Dim customerAccountNumber As String
Dim unitOfMeasureSymbol As String
Dim quantity As Decimal
Dim returnValue As ReadOnlyCollection(Of ProductPrice)

returnValue = instance.GetItemPrice(itemId, _
    inventoryDimensionId, barcode, customerAccountNumber, _
    unitOfMeasureSymbol, quantity)
```

``` csharp
public ReadOnlyCollection<ProductPrice> GetItemPrice(
    string itemId,
    string inventoryDimensionId,
    string barcode,
    string customerAccountNumber,
    string unitOfMeasureSymbol,
    decimal quantity
)
```

``` c++
public:
ReadOnlyCollection<ProductPrice^>^ GetItemPrice(
    String^ itemId, 
    String^ inventoryDimensionId, 
    String^ barcode, 
    String^ customerAccountNumber, 
    String^ unitOfMeasureSymbol, 
    Decimal quantity
)
```

#### Parameters

  - itemId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - inventoryDimensionId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - barcode  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - customerAccountNumber  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - unitOfMeasureSymbol  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - quantity  
    Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[ProductPrice](productprice-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
A collection of [ProductPrice](productprice-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[InventoryManager Class](inventorymanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)


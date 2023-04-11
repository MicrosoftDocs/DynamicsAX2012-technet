---
title: UnableToConvertUnitOfMeasureNotification.ItemUnitConversion Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ItemUnitConversion Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.UnableToConvertUnitOfMeasureNotification.ItemUnitConversion
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.unabletoconvertunitofmeasurenotification.itemunitconversion(v=AX.60)
ms:contentKeyID: 65316065
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.UnableToConvertUnitOfMeasureNotification.ItemUnitConversion
dev_langs:
- CSharp
- C++
- VB
---

# ItemUnitConversion Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the item unit conversion.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ItemUnitConversion As ItemUnitConversion
    Get
    Private Set
'Usage
Dim instance As UnableToConvertUnitOfMeasureNotification
Dim value As ItemUnitConversion

value = instance.ItemUnitConversion
```

``` csharp
[DataMemberAttribute]
public ItemUnitConversion ItemUnitConversion { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ItemUnitConversion^ ItemUnitConversion {
    ItemUnitConversion^ get ();
    private: void set (ItemUnitConversion^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemUnitConversion](itemunitconversion-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ItemUnitConversion](itemunitconversion-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[UnableToConvertUnitOfMeasureNotification Class](unabletoconvertunitofmeasurenotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


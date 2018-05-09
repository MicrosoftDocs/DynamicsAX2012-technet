---
title: Notification Class (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Notification Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.Notification
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.notification(v=AX.60)
ms:contentKeyID: 49832322
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Notification
dev_langs:
- CSharp
- C++
- VB
---

# Notification Class

Notification base class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public MustInherit Class Notification _
    Inherits CommerceEntity
'Usage
Dim instance As Notification
```

``` csharp
[DataContractAttribute]
public abstract class Notification : CommerceEntity
```

``` c++
[DataContractAttribute]
public ref class Notification abstract : public CommerceEntity
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
    Microsoft.Dynamics.Commerce.Runtime.DataModel.Notification  
      [Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountInvalidatedNotification](discountinvalidatednotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataModel.EmptyInventoryUnitOfMeasureNotification](emptyinventoryunitofmeasurenotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataModel.EmptyLineDeliveryOptionSetNotification](emptylinedeliveryoptionsetnotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataModel.EmptyOrderDeliveryOptionSetNotification](emptyorderdeliveryoptionsetnotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataModel.EmptyProductDeliveryOptionSetNotification](emptyproductdeliveryoptionsetnotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataModel.EmptySalesUnitOfMeasureNotification](emptysalesunitofmeasurenotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataModel.InsufficientQuantityAvailableNotification](insufficientquantityavailablenotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataModel.InvalidPriceNotification](invalidpricenotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataModel.InvalidShippingAddressNotification](invalidshippingaddressnotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataModel.InvalidTaxGroupNotification](invalidtaxgroupnotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataModel.InventoryNotFoundNotification](inventorynotfoundnotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemIdNotFoundInInventoryNotification](itemidnotfoundininventorynotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemOutOfStockNotification](itemoutofstocknotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataModel.MissingLineShippingInfoNotification](missinglineshippinginfonotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceChangedNotification](pricechangednotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductDiscontinuedFromChannelNotification](productdiscontinuedfromchannelnotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductMasterPageNotification](productmasterpagenotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeRequiredNotification](reasoncoderequirednotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataModel.UnableToConvertUnitOfMeasureNotification](unabletoconvertunitofmeasurenotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataModel.UnableToDetermineQuantityForStoresNotification](unabletodeterminequantityforstoresnotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataModel.UnableToDetermineQuantityNotification](unabletodeterminequantitynotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataModel.UnableToResolveListingIdsNotification](unabletoresolvelistingidsnotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataModel.UnableToRetrieveStoresNotification](unabletoretrievestoresnotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


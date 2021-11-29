---
title: DatabaseAccessor Class (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: DatabaseAccessor Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseAccessor
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.databaseaccessor(v=AX.60)
ms:contentKeyID: 62208203
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseAccessor
dev_langs:
- CSharp
- C++
- VB
---

# DatabaseAccessor Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The base data manager class which provides primitives for interacting with the channels database.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public MustInherit Class DatabaseAccessor _
    Inherits DataStoreAccessor
'Usage
Dim instance As DatabaseAccessor
```

``` csharp
public abstract class DatabaseAccessor : DataStoreAccessor
```

``` c++
public ref class DatabaseAccessor abstract : public DataStoreAccessor
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreAccessor](datastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)  
    Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseAccessor  
      [Microsoft.Dynamics.Commerce.Runtime.Data.AddressDataManager](addressdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Data.AffiliationDataManager](affiliationdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Data.BarcodeDataManager](barcodedatamanager-class-microsoft-dynamics-commerce-runtime-data.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDatabaseAccessor](channeldatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Data.ChargeDatabaseAccessor](chargedatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Data.CurrencyDatabaseAccessor](currencydatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Data.CustomerDataManager](customerdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Data.DeviceConfigurationDataManager](deviceconfigurationdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Data.DeviceDataManager](devicedatamanager-class-microsoft-dynamics-commerce-runtime-data.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Data.EmployeeDataManager](employeedatamanager-class-microsoft-dynamics-commerce-runtime-data.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Data.HardwareProfileDataManager](hardwareprofiledatamanager-class-microsoft-dynamics-commerce-runtime-data.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Data.InventoryDataManager](inventorydatamanager-class-microsoft-dynamics-commerce-runtime-data.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Data.ItemAvailabilityDataManager](itemavailabilitydatamanager-class-microsoft-dynamics-commerce-runtime-data.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Data.ItemDatabaseAccessor](itemdatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Data.LayoutDataManager](layoutdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Data.NumberSequenceSeedDataManager](numbersequenceseeddatamanager-class-microsoft-dynamics-commerce-runtime-data.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Data.OfflineProvisionDatabaseAccessor](offlineprovisiondatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Data.PaymentConnectorDataManager](paymentconnectordatamanager-class-microsoft-dynamics-commerce-runtime-data.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Data.PricingDatabaseAccessor](pricingdatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Data.ProductDatabaseAccessor](productdatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Data.ReasonCodeDatabaseAccessor](reasoncodedatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Data.SalesOrderDataManager](salesorderdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Data.SalesTransactionDataManager](salestransactiondatamanager-class-microsoft-dynamics-commerce-runtime-data.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Data.ShiftDataManager](shiftdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Data.ShippingDataManager](shippingdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Data.StockCountDataManager](stockcountdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Data.StoreLocatorDataManager](storelocatordatamanager-class-microsoft-dynamics-commerce-runtime-data.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Data.TaxDatabaseAccessor](taxdatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Data.TerminalDatabaseAccessor](terminaldatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Data.TillLayoutDataManager](tilllayoutdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Data.TransactionLogDataManager](transactionlogdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Data.UnitOfMeasureConversionDataManager](unitofmeasureconversiondatamanager-class-microsoft-dynamics-commerce-runtime-data.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


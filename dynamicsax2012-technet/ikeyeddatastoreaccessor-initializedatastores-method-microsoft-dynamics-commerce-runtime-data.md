---
title: IKeyedDataStoreAccessor.InitializeDataStores Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: InitializeDataStores Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IKeyedDataStoreAccessor.InitializeDataStores
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.ikeyeddatastoreaccessor.initializedatastores(v=AX.60)
ms:contentKeyID: 65319925
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IKeyedDataStoreAccessor.InitializeDataStores
dev_langs:
- CSharp
- C++
- VB
---

# InitializeDataStores Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Function InitializeDataStores As Lazy(Of Dictionary(Of DataStoreType, IDataStore))
'Usage
Dim instance As IKeyedDataStoreAccessor
Dim returnValue As Lazy(Of Dictionary(Of DataStoreType, IDataStore))

returnValue = instance.InitializeDataStores()
```

``` csharp
Lazy<Dictionary<DataStoreType, IDataStore>> InitializeDataStores()
```

``` c++
Lazy<Dictionary<DataStoreType, IDataStore^>^>^ InitializeDataStores()
```

#### Return Value

Type: Lazy\<[Dictionary](https://technet.microsoft.com/en-us/library/xfhwa508\(v=ax.60\))\<[DataStoreType](datastoretype-enumeration-microsoft-dynamics-commerce-runtime-data.md), [IDataStore](idatastore-interface-microsoft-dynamics-commerce-runtime-data.md)\>\>  

## See Also

#### Reference

[IKeyedDataStoreAccessor Interface](ikeyeddatastoreaccessor-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


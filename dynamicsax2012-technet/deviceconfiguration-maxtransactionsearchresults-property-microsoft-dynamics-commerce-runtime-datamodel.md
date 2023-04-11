---
title: DeviceConfiguration.MaxTransactionSearchResults Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MaxTransactionSearchResults Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.MaxTransactionSearchResults
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.maxtransactionsearchresults(v=AX.60)
ms:contentKeyID: 62202602
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.MaxTransactionSearchResults
dev_langs:
- CSharp
- C++
- VB
---

# MaxTransactionSearchResults Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the max transaction search result count.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("MAXTRANSACTIONSEARCHRESULTS")> _
<DataMemberAttribute> _
Public Property MaxTransactionSearchResults As Integer
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As Integer

value = instance.MaxTransactionSearchResults

instance.MaxTransactionSearchResults = value
```

``` csharp
[ColumnAttribute("MAXTRANSACTIONSEARCHRESULTS")]
[DataMemberAttribute]
public int MaxTransactionSearchResults { get; set; }
```

``` c++
[ColumnAttribute(L"MAXTRANSACTIONSEARCHRESULTS")]
[DataMemberAttribute]
public:
property int MaxTransactionSearchResults {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The max transaction search result count.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


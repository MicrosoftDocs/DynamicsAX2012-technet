---
title: SalesOrderDataManager.PurgeSalesTransactions Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PurgeSalesTransactions Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.SalesOrderDataManager.PurgeSalesTransactions(System.Int64,System.String,System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.salesorderdatamanager.purgesalestransactions(v=AX.60)
ms:contentKeyID: 65319220
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.SalesOrderDataManager.PurgeSalesTransactions
dev_langs:
- CSharp
- C++
- VB
---

# PurgeSalesTransactions Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Sub PurgeSalesTransactions ( _
    channelId As Long, _
    terminalId As String, _
    retentionDays As Integer _
)
'Usage
Dim instance As SalesOrderDataManager
Dim channelId As Long
Dim terminalId As String
Dim retentionDays As Integer

instance.PurgeSalesTransactions(channelId, _
    terminalId, retentionDays)
```

``` csharp
public void PurgeSalesTransactions(
    long channelId,
    string terminalId,
    int retentionDays
)
```

``` c++
public:
void PurgeSalesTransactions(
    long long channelId, 
    String^ terminalId, 
    int retentionDays
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - retentionDays  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[SalesOrderDataManager Class](salesorderdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


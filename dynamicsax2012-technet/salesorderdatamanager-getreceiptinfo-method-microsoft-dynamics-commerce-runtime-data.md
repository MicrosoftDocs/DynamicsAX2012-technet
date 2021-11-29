---
title: SalesOrderDataManager.GetReceiptInfo Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetReceiptInfo Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.SalesOrderDataManager.GetReceiptInfo(System.Boolean,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.salesorderdatamanager.getreceiptinfo(v=AX.60)
ms:contentKeyID: 65321276
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.SalesOrderDataManager.GetReceiptInfo
dev_langs:
- CSharp
- C++
- VB
---

# GetReceiptInfo Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetReceiptInfo ( _
    copyReceipt As Boolean, _
    layoutId As String, _
    settings As QueryResultSettings _
) As ReceiptInfo
'Usage
Dim instance As SalesOrderDataManager
Dim copyReceipt As Boolean
Dim layoutId As String
Dim settings As QueryResultSettings
Dim returnValue As ReceiptInfo

returnValue = instance.GetReceiptInfo(copyReceipt, _
    layoutId, settings)
```

``` csharp
public ReceiptInfo GetReceiptInfo(
    bool copyReceipt,
    string layoutId,
    QueryResultSettings settings
)
```

``` c++
public:
ReceiptInfo^ GetReceiptInfo(
    bool copyReceipt, 
    String^ layoutId, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - copyReceipt  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - layoutId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptInfo](receiptinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[SalesOrderDataManager Class](salesorderdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


---
title: TenderDropAndDeclareDataManager.GetTransaction Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: GetTransaction Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TenderDropAndDeclareDataManager.GetTransaction(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.tenderdropanddeclaredatamanager.gettransaction(v=AX.60)
ms:contentKeyID: 65321335
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TenderDropAndDeclareDataManager.GetTransaction
dev_langs:
- CSharp
- C++
- VB
---

# GetTransaction Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetTransaction ( _
    transactionId As String, _
    settings As QueryResultSettings _
) As DropAndDeclareTransaction
'Usage
Dim instance As TenderDropAndDeclareDataManager
Dim transactionId As String
Dim settings As QueryResultSettings
Dim returnValue As DropAndDeclareTransaction

returnValue = instance.GetTransaction(transactionId, _
    settings)
```

``` csharp
public DropAndDeclareTransaction GetTransaction(
    string transactionId,
    QueryResultSettings settings
)
```

``` c++
public:
DropAndDeclareTransaction^ GetTransaction(
    String^ transactionId, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - transactionId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DropAndDeclareTransaction](dropanddeclaretransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[TenderDropAndDeclareDataManager Class](tenderdropanddeclaredatamanager-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)


---
title: AffiliationDataManager.GetAffiliationByAffiliationId Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetAffiliationByAffiliationId Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.AffiliationDataManager.GetAffiliationByAffiliationId(System.Int64)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.affiliationdatamanager.getaffiliationbyaffiliationid(v=AX.60)
ms:contentKeyID: 65316480
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.AffiliationDataManager.GetAffiliationByAffiliationId
dev_langs:
- CSharp
- C++
- VB
---

# GetAffiliationByAffiliationId Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetAffiliationByAffiliationId ( _
    affiliationId As Long _
) As Affiliation
'Usage
Dim instance As AffiliationDataManager
Dim affiliationId As Long
Dim returnValue As Affiliation

returnValue = instance.GetAffiliationByAffiliationId(affiliationId)
```

``` csharp
public Affiliation GetAffiliationByAffiliationId(
    long affiliationId
)
```

``` c++
public:
Affiliation^ GetAffiliationByAffiliationId(
    long long affiliationId
)
```

#### Parameters

  - affiliationId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Affiliation](affiliation-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[AffiliationDataManager Class](affiliationdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


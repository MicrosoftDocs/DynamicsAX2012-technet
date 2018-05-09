---
title: ICurrencyV1.GetAllCurrTypes Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: GetAllCurrTypes Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICurrencyV1.GetAllCurrTypes(System.String,System.String,System.Collections.ArrayList@)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.icurrencyv1.getallcurrtypes(v=AX.60)
ms:contentKeyID: 47344438
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICurrencyV1.GetAllCurrTypes
dev_langs:
- CSharp
- C++
- VB
---

# GetAllCurrTypes Method

The current implementation fetches all currency codes available for the current DataareaId value.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub GetAllCurrTypes ( _
    localCurrencyCode As String, _
    usedCurrencyCode As String, _
    ByRef currTypes As ArrayList _
)
'Usage
Dim instance As ICurrencyV1
Dim localCurrencyCode As String
Dim usedCurrencyCode As String
Dim currTypes As ArrayList

instance.GetAllCurrTypes(localCurrencyCode, _
    usedCurrencyCode, currTypes)
```

``` csharp
void GetAllCurrTypes(
    string localCurrencyCode,
    string usedCurrencyCode,
    ref ArrayList currTypes
)
```

``` c++
void GetAllCurrTypes(
    String^ localCurrencyCode, 
    String^ usedCurrencyCode, 
    ArrayList^% currTypes
)
```

#### Parameters

  - localCurrencyCode  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - usedCurrencyCode  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - currTypes  
    Type: [System.Collections.ArrayList](https://technet.microsoft.com/en-us/library/7x4b0a97\(v=ax.60\))  

## See Also

#### Reference

[ICurrencyV1 Interface](icurrencyv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)


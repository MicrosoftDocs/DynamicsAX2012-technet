---
title: IAfflicationV1.AddAffiliationsRequest Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: AddAffiliationsRequest Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IAfflicationV1.AddAffiliationsRequest(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction,System.Collections.Generic.IList{Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IAffiliation})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iafflicationv1.addaffiliationsrequest(v=AX.60)
ms:contentKeyID: 62203931
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IAfflicationV1.AddAffiliationsRequest
dev_langs:
- CSharp
- C++
- VB
---

# AddAffiliationsRequest Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Add affiliation request and return true if added to transactin successfully.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function AddAffiliationsRequest ( _
    retailTransaction As IRetailTransaction, _
    affiliations As IList(Of IAffiliation) _
) As Boolean
'Usage
Dim instance As IAfflicationV1
Dim retailTransaction As IRetailTransaction
Dim affiliations As IList(Of IAffiliation)
Dim returnValue As Boolean

returnValue = instance.AddAffiliationsRequest(retailTransaction, _
    affiliations)
```

``` csharp
bool AddAffiliationsRequest(
    IRetailTransaction retailTransaction,
    IList<IAffiliation> affiliations
)
```

``` c++
bool AddAffiliationsRequest(
    IRetailTransaction^ retailTransaction, 
    IList<IAffiliation^>^ affiliations
)
```

#### Parameters

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - affiliations  
    Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[IAffiliation](iaffiliation-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)\>  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Return true when add sucessfully, otherwise return false  

## See Also

#### Reference

[IAfflicationV1 Interface](iafflicationv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)


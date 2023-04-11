---
title: IAfflicationV1.SelectAffiliations Method (IList(IAffiliation)) (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: SelectAffiliations Method (IList(IAffiliation))
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IAfflicationV1.SelectAffiliations(System.Collections.Generic.IList{Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IAffiliation})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iafflicationv1.selectaffiliations(v=AX.60)
ms:contentKeyID: 62204719
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SelectAffiliations Method (IList(IAffiliation))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Show affiliation page and return selected affiliations.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function SelectAffiliations ( _
    selectedAffiliations As IList(Of IAffiliation) _
) As IList(Of IAffiliation)
'Usage
Dim instance As IAfflicationV1
Dim selectedAffiliations As IList(Of IAffiliation)
Dim returnValue As IList(Of IAffiliation)

returnValue = instance.SelectAffiliations(selectedAffiliations)
```

``` csharp
IList<IAffiliation> SelectAffiliations(
    IList<IAffiliation> selectedAffiliations
)
```

``` c++
IList<IAffiliation^>^ SelectAffiliations(
    IList<IAffiliation^>^ selectedAffiliations
)
```

#### Parameters

  - selectedAffiliations  
    Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[IAffiliation](iaffiliation-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)\>  

#### Return Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[IAffiliation](iaffiliation-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)\>  
Select result of affiliation.  

## See Also

#### Reference

[IAfflicationV1 Interface](iafflicationv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[SelectAffiliations Overload](iafflicationv1-selectaffiliations-method-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)


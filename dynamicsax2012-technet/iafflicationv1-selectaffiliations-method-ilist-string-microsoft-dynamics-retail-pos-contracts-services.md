---
title: IAfflicationV1.SelectAffiliations Method (IList(String)) (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: SelectAffiliations Method (IList(String))
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IAfflicationV1.SelectAffiliations(System.Collections.Generic.IList{System.String})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.iafflicationv1.selectaffiliations(v=AX.60)
ms:contentKeyID: 62205927
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SelectAffiliations Method (IList(String))

Show affiliation page and return selected affiliations.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function SelectAffiliations ( _
    nameOfSelectedAffiliations As IList(Of String) _
) As IList(Of IAffiliation)
'Usage
Dim instance As IAfflicationV1
Dim nameOfSelectedAffiliations As IList(Of String)
Dim returnValue As IList(Of IAffiliation)

returnValue = instance.SelectAffiliations(nameOfSelectedAffiliations)
```

``` csharp
IList<IAffiliation> SelectAffiliations(
    IList<string> nameOfSelectedAffiliations
)
```

``` c++
IList<IAffiliation^>^ SelectAffiliations(
    IList<String^>^ nameOfSelectedAffiliations
)
```

#### Parameters

  - nameOfSelectedAffiliations  
    Type: [System.Collections.Generic.IList](https://technet.microsoft.com/en-us/library/5y536ey6\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  

#### Return Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/en-us/library/5y536ey6\(v=ax.60\))\<[IAffiliation](iaffiliation-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)\>  
Select result of affiliation.  

## See Also

#### Reference

[IAfflicationV1 Interface](iafflicationv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[SelectAffiliations Overload](iafflicationv1-selectaffiliations-method-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)


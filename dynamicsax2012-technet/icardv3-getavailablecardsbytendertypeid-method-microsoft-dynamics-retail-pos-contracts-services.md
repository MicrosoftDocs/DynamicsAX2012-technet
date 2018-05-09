---
title: ICardV3.GetAvailableCardsByTenderTypeId Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: GetAvailableCardsByTenderTypeId Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICardV3.GetAvailableCardsByTenderTypeId(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.icardv3.getavailablecardsbytendertypeid(v=AX.60)
ms:contentKeyID: 62205942
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICardV3.GetAvailableCardsByTenderTypeId
dev_langs:
- CSharp
- C++
- VB
---

# GetAvailableCardsByTenderTypeId Method

Will return a collection of card info from the database specific to the current store for the input tender type id.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function GetAvailableCardsByTenderTypeId ( _
    tenderTypeId As String _
) As IEnumerable(Of ICardInfo)
'Usage
Dim instance As ICardV3
Dim tenderTypeId As String
Dim returnValue As IEnumerable(Of ICardInfo)

returnValue = instance.GetAvailableCardsByTenderTypeId(tenderTypeId)
```

``` csharp
IEnumerable<ICardInfo> GetAvailableCardsByTenderTypeId(
    string tenderTypeId
)
```

``` c++
IEnumerable<ICardInfo^>^ GetAvailableCardsByTenderTypeId(
    String^ tenderTypeId
)
```

#### Parameters

  - tenderTypeId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[ICardInfo](icardinfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\)).  

## Remarks

This will return only a distinct collection of cards that can be used by the system.

The card info does not contain full info (like card number ranges, etc).

## See Also

#### Reference

[ICardV3 Interface](icardv3-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)


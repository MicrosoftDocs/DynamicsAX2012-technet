---
title: IPeriodicDiscountV1.GetDiscountOfferDetails Method  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: GetDiscountOfferDetails Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPeriodicDiscountV1.GetDiscountOfferDetails(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iperiodicdiscountv1.getdiscountofferdetails(v=AX.60)
ms:contentKeyID: 49850216
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPeriodicDiscountV1.GetDiscountOfferDetails
dev_langs:
- CSharp
- C++
- VB
---

# GetDiscountOfferDetails Method

Get barcode, Discountcode associated with an Offer

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function GetDiscountOfferDetails ( _
    offerId As String _
) As DataTable
'Usage
Dim instance As IPeriodicDiscountV1
Dim offerId As String
Dim returnValue As DataTable

returnValue = instance.GetDiscountOfferDetails(offerId)
```

``` csharp
DataTable GetDiscountOfferDetails(
    string offerId
)
```

``` c++
DataTable^ GetDiscountOfferDetails(
    String^ offerId
)
```

#### Parameters

  - offerId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Data.DataTable](https://technet.microsoft.com/library/9186hy08\(v=ax.60\))  

## See Also

#### Reference

[IPeriodicDiscountV1 Interface](iperiodicdiscountv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)


---
title: ICustomFieldV1.PopulateItemReceiptFields Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PopulateItemReceiptFields Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICustomFieldV1.PopulateItemReceiptFields(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Retail.Pos.Contracts.Services.CustomFieldValue},Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.icustomfieldv1.populateitemreceiptfields(v=AX.60)
ms:contentKeyID: 47343941
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICustomFieldV1.PopulateItemReceiptFields
dev_langs:
- CSharp
- C++
- VB
---

# PopulateItemReceiptFields Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Populates the custom ItemReceipt fields.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function PopulateItemReceiptFields ( _
    fields As IEnumerable(Of CustomFieldValue), _
    saleLineItem As ISaleLineItem, _
    posTransaction As IPosTransaction _
) As IDictionary(Of String, String)
'Usage
Dim instance As ICustomFieldV1
Dim fields As IEnumerable(Of CustomFieldValue)
Dim saleLineItem As ISaleLineItem
Dim posTransaction As IPosTransaction
Dim returnValue As IDictionary(Of String, String)

returnValue = instance.PopulateItemReceiptFields(fields, _
    saleLineItem, posTransaction)
```

``` csharp
IDictionary<string, string> PopulateItemReceiptFields(
    IEnumerable<CustomFieldValue> fields,
    ISaleLineItem saleLineItem,
    IPosTransaction posTransaction
)
```

``` c++
IDictionary<String^, String^>^ PopulateItemReceiptFields(
    IEnumerable<CustomFieldValue>^ fields, 
    ISaleLineItem^ saleLineItem, 
    IPosTransaction^ posTransaction
)
```

#### Parameters

  - fields  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[CustomFieldValue](customfieldvalue-structure-microsoft-dynamics-retail-pos-contracts-services.md)\>  

<!-- end list -->

  - saleLineItem  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem](isalelineitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

#### Return Value

Type: [System.Collections.Generic.IDictionary](https://technet.microsoft.com/library/s4ys34ea\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)), [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
A dictionary of \[Field Name, Field Value\] pairs.  

## See Also

#### Reference

[ICustomFieldV1 Interface](icustomfieldv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)


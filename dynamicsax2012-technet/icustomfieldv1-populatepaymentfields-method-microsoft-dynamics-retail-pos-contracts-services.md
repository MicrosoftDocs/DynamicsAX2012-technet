---
title: ICustomFieldV1.PopulatePaymentFields Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PopulatePaymentFields Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICustomFieldV1.PopulatePaymentFields(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Retail.Pos.Contracts.Services.CustomFieldValue},Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITenderLineItem,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.icustomfieldv1.populatepaymentfields(v=AX.60)
ms:contentKeyID: 47344252
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICustomFieldV1.PopulatePaymentFields
dev_langs:
- CSharp
- C++
- VB
---

# PopulatePaymentFields Method

Populates the custom payment fields.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function PopulatePaymentFields ( _
    fields As IEnumerable(Of CustomFieldValue), _
    tenderLineItem As ITenderLineItem, _
    posTransaction As IPosTransaction _
) As IDictionary(Of String, String)
'Usage
Dim instance As ICustomFieldV1
Dim fields As IEnumerable(Of CustomFieldValue)
Dim tenderLineItem As ITenderLineItem
Dim posTransaction As IPosTransaction
Dim returnValue As IDictionary(Of String, String)

returnValue = instance.PopulatePaymentFields(fields, _
    tenderLineItem, posTransaction)
```

``` csharp
IDictionary<string, string> PopulatePaymentFields(
    IEnumerable<CustomFieldValue> fields,
    ITenderLineItem tenderLineItem,
    IPosTransaction posTransaction
)
```

``` c++
IDictionary<String^, String^>^ PopulatePaymentFields(
    IEnumerable<CustomFieldValue>^ fields, 
    ITenderLineItem^ tenderLineItem, 
    IPosTransaction^ posTransaction
)
```

#### Parameters

  - fields  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[CustomFieldValue](customfieldvalue-structure-microsoft-dynamics-retail-pos-contracts-services.md)\>  

<!-- end list -->

  - tenderLineItem  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITenderLineItem](itenderlineitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

#### Return Value

Type: [System.Collections.Generic.IDictionary](https://technet.microsoft.com/en-us/library/s4ys34ea\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)), [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  
A dictionary of \[Field Name, Field Value\] pairs.  

## See Also

#### Reference

[ICustomFieldV1 Interface](icustomfieldv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)


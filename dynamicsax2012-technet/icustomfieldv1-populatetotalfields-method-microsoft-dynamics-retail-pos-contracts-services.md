---
title: ICustomFieldV1.PopulateTotalFields Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PopulateTotalFields Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICustomFieldV1.PopulateTotalFields(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Retail.Pos.Contracts.Services.CustomFieldValue},Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.icustomfieldv1.populatetotalfields(v=AX.60)
ms:contentKeyID: 47344152
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICustomFieldV1.PopulateTotalFields
dev_langs:
- CSharp
- C++
- VB
---

# PopulateTotalFields Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Populates custom total fields.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function PopulateTotalFields ( _
    fields As IEnumerable(Of CustomFieldValue), _
    posTransaction As IPosTransaction _
) As IDictionary(Of String, String)
'Usage
Dim instance As ICustomFieldV1
Dim fields As IEnumerable(Of CustomFieldValue)
Dim posTransaction As IPosTransaction
Dim returnValue As IDictionary(Of String, String)

returnValue = instance.PopulateTotalFields(fields, _
    posTransaction)
```

``` csharp
IDictionary<string, string> PopulateTotalFields(
    IEnumerable<CustomFieldValue> fields,
    IPosTransaction posTransaction
)
```

``` c++
IDictionary<String^, String^>^ PopulateTotalFields(
    IEnumerable<CustomFieldValue>^ fields, 
    IPosTransaction^ posTransaction
)
```

#### Parameters

  - fields  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[CustomFieldValue](customfieldvalue-structure-microsoft-dynamics-retail-pos-contracts-services.md)\>  

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


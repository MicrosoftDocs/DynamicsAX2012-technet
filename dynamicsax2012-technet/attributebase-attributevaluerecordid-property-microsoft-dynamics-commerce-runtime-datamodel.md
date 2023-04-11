---
title: AttributeBase.AttributeValueRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AttributeValueRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeBase.AttributeValueRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.attributebase.attributevaluerecordid(v=AX.60)
ms:contentKeyID: 49846717
author: tfehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeBase.AttributeValueRecordId
dev_langs:
- CSharp
- C++
- VB
---

# AttributeValueRecordId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the record identifier of the attribute value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ATTRIBUTEVALUERECID")> _
<DataMemberAttribute> _
Public Property AttributeValueRecordId As Long
    Get
    Set
'Usage
Dim instance As AttributeBase
Dim value As Long

value = instance.AttributeValueRecordId

instance.AttributeValueRecordId = value
```

``` csharp
[ColumnAttribute("ATTRIBUTEVALUERECID")]
[DataMemberAttribute]
public long AttributeValueRecordId { get; set; }
```

``` c++
[ColumnAttribute(L"ATTRIBUTEVALUERECID")]
[DataMemberAttribute]
public:
property long long AttributeValueRecordId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The record identifier of the attribute value.  

## See Also

#### Reference

[AttributeBase Class](attributebase-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


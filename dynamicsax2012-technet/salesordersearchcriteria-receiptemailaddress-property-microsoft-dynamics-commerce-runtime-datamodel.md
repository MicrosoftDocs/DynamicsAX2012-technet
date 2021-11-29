---
title: SalesOrderSearchCriteria.ReceiptEmailAddress Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReceiptEmailAddress Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrderSearchCriteria.ReceiptEmailAddress
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesordersearchcriteria.receiptemailaddress(v=AX.60)
ms:contentKeyID: 62213145
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrderSearchCriteria.ReceiptEmailAddress
dev_langs:
- CSharp
- C++
- VB
---

# ReceiptEmailAddress Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the receipt email address for filtering.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ReceiptEmailAddress As String
    Get
    Set
'Usage
Dim instance As SalesOrderSearchCriteria
Dim value As String

value = instance.ReceiptEmailAddress

instance.ReceiptEmailAddress = value
```

``` csharp
[DataMemberAttribute]
public string ReceiptEmailAddress { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ReceiptEmailAddress {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[SalesOrderSearchCriteria Class](salesordersearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


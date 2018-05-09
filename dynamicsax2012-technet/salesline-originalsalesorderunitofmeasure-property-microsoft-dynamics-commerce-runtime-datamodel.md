---
title: SalesLine.OriginalSalesOrderUnitOfMeasure Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OriginalSalesOrderUnitOfMeasure Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.OriginalSalesOrderUnitOfMeasure
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.originalsalesorderunitofmeasure(v=AX.60)
ms:contentKeyID: 49830735
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.OriginalSalesOrderUnitOfMeasure
dev_langs:
- CSharp
- C++
- VB
---

# OriginalSalesOrderUnitOfMeasure Property

Gets or sets the sales unit of measure set on the item in AX.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property OriginalSalesOrderUnitOfMeasure As String
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As String

value = instance.OriginalSalesOrderUnitOfMeasure

instance.OriginalSalesOrderUnitOfMeasure = value
```

``` csharp
[DataMemberAttribute]
public string OriginalSalesOrderUnitOfMeasure { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ OriginalSalesOrderUnitOfMeasure {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


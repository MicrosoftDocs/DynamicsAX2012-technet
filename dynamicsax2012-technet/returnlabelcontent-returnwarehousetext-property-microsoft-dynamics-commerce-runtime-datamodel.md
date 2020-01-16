---
title: ReturnLabelContent.ReturnWarehouseText Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReturnWarehouseText Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReturnLabelContent.ReturnWarehouseText
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.returnlabelcontent.returnwarehousetext(v=AX.60)
ms:contentKeyID: 65316068
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReturnLabelContent.ReturnWarehouseText
dev_langs:
- CSharp
- C++
- VB
---

# ReturnWarehouseText Property

Gets or sets the return warehouse text.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ReturnWarehouseText As String
    Get
    Set
'Usage
Dim instance As ReturnLabelContent
Dim value As String

value = instance.ReturnWarehouseText

instance.ReturnWarehouseText = value
```

``` csharp
[DataMemberAttribute]
public string ReturnWarehouseText { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ReturnWarehouseText {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The return warehouse text, if any.  

## See Also

#### Reference

[ReturnLabelContent Class](returnlabelcontent-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


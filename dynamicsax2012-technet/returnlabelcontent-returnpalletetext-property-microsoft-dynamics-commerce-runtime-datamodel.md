---
title: ReturnLabelContent.ReturnPalleteText Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReturnPalleteText Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReturnLabelContent.ReturnPalleteText
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.returnlabelcontent.returnpalletetext(v=AX.60)
ms:contentKeyID: 65322138
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReturnLabelContent.ReturnPalleteText
dev_langs:
- CSharp
- C++
- VB
---

# ReturnPalleteText Property

Gets or sets the return palette text.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ReturnPalleteText As String
    Get
    Set
'Usage
Dim instance As ReturnLabelContent
Dim value As String

value = instance.ReturnPalleteText

instance.ReturnPalleteText = value
```

``` csharp
[DataMemberAttribute]
public string ReturnPalleteText { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ReturnPalleteText {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The return palette, if any.  

## See Also

#### Reference

[ReturnLabelContent Class](returnlabelcontent-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


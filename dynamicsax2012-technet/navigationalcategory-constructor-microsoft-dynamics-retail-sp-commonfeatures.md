---
title: NavigationalCategory Constructor  (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: NavigationalCategory Constructor
ms:assetid: M:Microsoft.Dynamics.Retail.SP.CommonFeatures.NavigationalCategory.#ctor(Microsoft.Dynamics.Retail.SP.CommonFeatures.NavigationalCategory,System.String,System.Collections.Generic.IList{System.String},System.String,System.String,System.String,Microsoft.Dynamics.Retail.SP.CommonFeatures.SubMenuType,System.String,System.Int32,System.Int32,System.Int32,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commonfeatures.navigationalcategory.navigationalcategory(v=AX.60)
ms:contentKeyID: 62206660
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.NavigationalCategory.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# NavigationalCategory Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [NavigationalCategory](navigationalcategory-class-microsoft-dynamics-retail-sp-commonfeatures.md) class.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    parent As NavigationalCategory, _
    name As String, _
    images As IList(Of String), _
    defaultImage As String, _
    url As String, _
    description As String, _
    subMenuType As SubMenuType, _
    themeName As String, _
    sortIndex As Integer, _
    columnIndex As Integer, _
    indexInsideColumn As Integer, _
    isStatic As Boolean _
)
'Usage
Dim parent As NavigationalCategory
Dim name As String
Dim images As IList(Of String)
Dim defaultImage As String
Dim url As String
Dim description As String
Dim subMenuType As SubMenuType
Dim themeName As String
Dim sortIndex As Integer
Dim columnIndex As Integer
Dim indexInsideColumn As Integer
Dim isStatic As Boolean

Dim instance As New NavigationalCategory(parent, _
    name, images, defaultImage, url, description, _
    subMenuType, themeName, sortIndex, _
    columnIndex, indexInsideColumn, _
    isStatic)
```

``` csharp
public NavigationalCategory(
    NavigationalCategory parent,
    string name,
    IList<string> images,
    string defaultImage,
    string url,
    string description,
    SubMenuType subMenuType,
    string themeName,
    int sortIndex,
    int columnIndex,
    int indexInsideColumn,
    bool isStatic
)
```

``` c++
public:
NavigationalCategory(
    NavigationalCategory^ parent, 
    String^ name, 
    IList<String^>^ images, 
    String^ defaultImage, 
    String^ url, 
    String^ description, 
    SubMenuType subMenuType, 
    String^ themeName, 
    int sortIndex, 
    int columnIndex, 
    int indexInsideColumn, 
    bool isStatic
)
```

#### Parameters

  - parent  
    Type: [Microsoft.Dynamics.Retail.SP.CommonFeatures.NavigationalCategory](navigationalcategory-class-microsoft-dynamics-retail-sp-commonfeatures.md)  

<!-- end list -->

  - name  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - images  
    Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - defaultImage  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - url  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - description  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - subMenuType  
    Type: [Microsoft.Dynamics.Retail.SP.CommonFeatures.SubMenuType](submenutype-enumeration-microsoft-dynamics-retail-sp-commonfeatures.md)  

<!-- end list -->

  - themeName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - sortIndex  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

<!-- end list -->

  - columnIndex  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

<!-- end list -->

  - indexInsideColumn  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

<!-- end list -->

  - isStatic  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[NavigationalCategory Class](navigationalcategory-class-microsoft-dynamics-retail-sp-commonfeatures.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)


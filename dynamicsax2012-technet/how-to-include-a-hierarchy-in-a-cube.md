---
title: 'How to: Include a hierarchy in a cube'
TOCTitle: 'How to: Include a hierarchy in a cube'
ms:assetid: 63b7a0f8-f779-44cc-9eb3-75d618a3b383
ms:mtpsurl: https://technet.microsoft.com/library/Mt584219(v=AX.60)
ms:contentKeyID: 70094429
author: Khairunj
ms.date: 10/05/2015
mtps_version: v=AX.60
---

# How to: Include a hierarchy in a cube 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


Organizational hierarchies enable an organization to define various hierarchies among legal entities and operating units for reporting and operational purposes. You can define an organizational hierarchy to establish a relationship between legal entities or between operating units within a given legal entity. For examples, see [Example organizational hierarchies](example-organizational-hierarchies.md).

A specific example of an organizational hierarchy can be found in the Retail cube in Microsoft Dynamics AX 2012 R2. The Organization Unit dimension in the Retail cube enables the user to navigate the Retail channel hierarchy. If a change is made to the channel hierarchy, such as an addition of a new store, the changes are reflected automatically the next time the cube is processed.

A hierarchy that shows a recursive relationship, such as in the example mentioned above, is referred to as a parent-child hierarchy in SQL Server Analysis Services (SSAS). You can add parent-child organizational hierarchies to other cubes.

It is possible that there are many organizational hierarchies defined in your AX 2012 installation. Some organizational hierarchies may be used by specific business processes, such as centralized payments from different legal entities, while others may be used for representing a corporate hierarchy. Since there are many different types of organizational hierarchies, you need to select the relevant hierarchy defined by your organization to be included in the cube.

In this article, we will add a legal entity hierarchy to the Accounts Receivable cube. This includes:

1.  Create an organizational hierarchy dimension

2.  Add the organization ID to the measure

3.  Create the business intelligence project

4.  Edit the business intelligence project in Visual Studio BI

## Create an organizational hierarchy dimension

1.  Create a hierarchy query using the following steps. You’ll create the new query based on the DirPartyTable, OMInternanlOrganization, and OMHierarchyRelationShip tables.
    
    1.  In the AOT, right-click the **Queries** node, and then click **New Query**.
    
    2.  Select the node for the query.
    
    3.  In the **Properties** window, type **OMHierarchyQuery** in the **Name** property.
    
    4.  Select the **Fields** node. In the **Properties** window, set the **Dynamics** property to **Yes**.
    
    5.  Expand the **Data Sources** node.
    
    6.  Right-click the **Data Sources** node, and then click **New Data Source**.
    
    7.  In the **Properties** window, type **DirPartyTable** in the **Table** property.
    
    8.  Select the **Field** node. In the **Properties** window, set the **Dynamics** property to **Yes**.
    
    9.  Right-click the **Data Sources** node under **DirPartyTable**, and then click **New Data Source**.
    
    10. In the **Properties** window, type **OMInternalOrganization** in the **Table** property.
    
    11. Select the **Field** node. In the **Properties** windows, set the **Dynamics** property to **Yes**.
    
    12. Right-click the **Data Sources** node under **OMInternalOrganization**, and then click **New Data Source**.
    
    13. In the **Properties** window, type **OMHierarchyRelationship** in the **Table** property.
    
    14. Select the **Field** node. In the **Properties** windows, set the **Dynamics** property to **Yes**.
    
    15. Right-click the **Relations** node under **OMInternalOrganization**, and then click **New Relation**.
    
    16. In the **Properties** window, specify:
        
        <table>
        <colgroup>
        <col style="width: 50%" />
        <col style="width: 50%" />
        </colgroup>
        <thead>
        <tr class="header">
        <th><p>Property</p></th>
        <th><p>Value</p></th>
        </tr>
        </thead>
        <tbody>
        <tr class="odd">
        <td><p>JoinDataSource</p></td>
        <td><p>DirPartyTable_1</p></td>
        </tr>
        <tr class="even">
        <td><p>Field</p></td>
        <td><p>RecId</p></td>
        </tr>
        <tr class="odd">
        <td><p>RelatedField</p></td>
        <td><p>RedId</p></td>
        </tr>
        </tbody>
        </table>
    
    17. Expand the **OMHierarchyRelationship\_1** node.
    
    18. Right-click the **Relations** node under **OMHierarchyRelationship**, and then click **New Relation**.
    
    19. In the **Properties** window, specify:
        
        <table>
        <colgroup>
        <col style="width: 50%" />
        <col style="width: 50%" />
        </colgroup>
        <thead>
        <tr class="header">
        <th><p>Property</p></th>
        <th><p>Value</p></th>
        </tr>
        </thead>
        <tbody>
        <tr class="odd">
        <td><p>JoinDataSource</p></td>
        <td><p>OMInternalOrganization_1</p></td>
        </tr>
        <tr class="even">
        <td><p>Field</p></td>
        <td><p>RecId</p></td>
        </tr>
        <tr class="odd">
        <td><p>RelatedField</p></td>
        <td><p>ChildOrganization</p></td>
        </tr>
        </tbody>
        </table>


2.  Create a hierarchy view using the following steps.
    
    1.  In the AOT, expand the **Data Dictionary** node, and right-click **Views**. Then click **New View**.
    
    2.  Select the node for the query.
    
    3.  In the **Properties** window, type **OMHierarchyView** in the **Name** property.
    
    4.  In the view, expand the **Metadata** node.
    
    5.  Drag and drop **OMHierarchyQuery** under the **Metadata** node.
    
    6.  Right-click the **Fields** node, and then select **New Field**.
    
    7.  In the **Properties** window, specify:
        
        <table>
        <colgroup>
        <col style="width: 50%" />
        <col style="width: 50%" />
        </colgroup>
        <thead>
        <tr class="header">
        <th><p>Property</p></th>
        <th><p>Value</p></th>
        </tr>
        </thead>
        <tbody>
        <tr class="odd">
        <td><p>DataSource</p></td>
        <td><p>DirPartyTable_1</p></td>
        </tr>
        <tr class="even">
        <td><p>DataField</p></td>
        <td><p>Name</p></td>
        </tr>
        </tbody>
        </table>
    
    8.  Right-click the **Fields** node, and then select **New Field**.
    
    9.  In the **Properties** window, specify:
        
        <table>
        <colgroup>
        <col style="width: 50%" />
        <col style="width: 50%" />
        </colgroup>
        <thead>
        <tr class="header">
        <th><p>Property</p></th>
        <th><p>Value</p></th>
        </tr>
        </thead>
        <tbody>
        <tr class="odd">
        <td><p>DataSource</p></td>
        <td><p>OMHierarchyRelationship_1</p></td>
        </tr>
        <tr class="even">
        <td><p>DataField</p></td>
        <td><p>ParentOrganization</p></td>
        </tr>
        </tbody>
        </table>


3.  Use the following steps to add the hierarchy view to the cube perspective.
    
    1.  In the AOT, expand the **Data Dictionary** \> **Perspectives** node.
    
    2.  Find the perspective representing the cube that you want to add the organizational hierarchy to. This example uses the CustCube (Accounts receivable cube).
    
    3.  Expand the **CustCube** perspective and then the **Views** node.
    
    4.  Drag and drop **OMHierarchyView** under **Views**.
    
    5.  Select **OMHierarchyView**.
    
    6.  In the **Properties** window, specify:
        
        <table>
        <colgroup>
        <col style="width: 50%" />
        <col style="width: 50%" />
        </colgroup>
        <thead>
        <tr class="header">
        <th><p>Property</p></th>
        <th><p>Value</p></th>
        </tr>
        </thead>
        <tbody>
        <tr class="odd">
        <td><p>AnalysisDemensionLabel</p></td>
        <td><p>Org</p></td>
        </tr>
        <tr class="even">
        <td><p>AnalysisKeyAttributeLabel</p></td>
        <td><p>Org</p></td>
        </tr>
        </tbody>
        </table>
    
    7.  Expand the **Fields** node and select the **Name** field.
    
    8.  In the **Properties** window, specify:
        
        <table>
        <colgroup>
        <col style="width: 50%" />
        <col style="width: 50%" />
        </colgroup>
        <thead>
        <tr class="header">
        <th><p>Property</p></th>
        <th><p>Value</p></th>
        </tr>
        </thead>
        <tbody>
        <tr class="odd">
        <td><p>AnalysisUsage</p></td>
        <td><p>Attribute</p></td>
        </tr>
        </tbody>
        </table>
    
    9.  Select the **ParentOrganization** field.
    
    10. In the **Properties** window, specify:
        
        <table>
        <colgroup>
        <col style="width: 50%" />
        <col style="width: 50%" />
        </colgroup>
        <thead>
        <tr class="header">
        <th><p>Property</p></th>
        <th><p>Value</p></th>
        </tr>
        </thead>
        <tbody>
        <tr class="odd">
        <td><p>AnalysisUsage</p></td>
        <td><p>Attribute</p></td>
        </tr>
        <tr class="even">
        <td><p>AnalysisLabel</p></td>
        <td><p>Parent org</p></td>
        </tr>
        </tbody>
        </table>


## Add the organization ID to the measure

In order to analyze the cube based on the newly created dimension, add the organization ID to the measure cube query.

In this example, we will add the organization ID to the Customer transaction measure. In the CustCube perspective, we can see that the Customer transactions table is created from the CustTrans table. Therefore, we will have to create the query based on CustTrans and add the CompanyInfo reference.

1.  Create an extended customer transaction query using the following steps.
    
    1.  In the AOT, right-click the **Queries** node, and then click **New Query**.
    
    2.  Select the node for the query.
    
    3.  In the **Properties** window, type **CustTransExt** in the **Name** property.
    
    4.  Select the **Fields** node. In the **Properties** window, set the **Dynamics** property to **Yes**.
    
    5.  Expand the **Data Sources** node.
    
    6.  Right-click the **Data Sources** node, and then click **New Data Source**.
    
    7.  In the **Properties** window, type **CompanyInfo** in the **Table** property.
    
    8.  Select the **Fields** node. In the **Properties** window, set the **Dynamics** property to **Yes**.
    
    9.  Right-click the **Relations** node under **CompanyInfo**, and then click **New Relation**.
    
    10. In the **Properties** window, specify:
        
        <table>
        <colgroup>
        <col style="width: 50%" />
        <col style="width: 50%" />
        </colgroup>
        <thead>
        <tr class="header">
        <th><p>Property</p></th>
        <th><p>Value</p></th>
        </tr>
        </thead>
        <tbody>
        <tr class="odd">
        <td><p>JoinDataSource</p></td>
        <td><p>CustTrans_1</p></td>
        </tr>
        <tr class="even">
        <td><p>Field</p></td>
        <td><p>dataAreaId</p></td>
        </tr>
        <tr class="odd">
        <td><p>RelatedField</p></td>
        <td><p>DataArea</p></td>
        </tr>
        </tbody>
        </table>


2.  Create a view of customer transactions using the following steps.
    
    1.  In the AOT, expand the **Data Dictionary** node, and right-click the **Views** node. Then click **New View**.
    
    2.  Select the node for the query.
    
    3.  In the **Properties** window, type **CustTransExt** in the **Name** property.
    
    4.  In the view, expand the **Metadata** node.
    
    5.  Drag and drop the **CustTransExt** query under the **Metadata** node.
    
    6.  Drag and drop the following fields from the **CustTransExt** query to the view. (You’ll drag and drop the same fields which were mentioned in the CustCube perspective in the **CustTran** table).
        
        From data source **CustTrans**:
        
          - **AccountNum**
        
          - **TransDate**
        
          - **AmountCur**
        
          - **SettleAmount**
        
          - **AmountMST**
        
          - **SettleAmountMST**
        
          - **CurrencyCode**
        
          - **DueDate**
        
          - **LastSettleDate**
        
          - **Closed**
        
          - **TransType**
        
          - **Approved**
        
          - **DocumentDate**
        
          - **PaymMode**
        
          - **DefaultDimension**
        
          - **CustBillingClassification**
        
        From data source **CompanyInfo**:
        
          - **RecId**
            

            > [!NOTE]
            > <P>For this field, change the <STRONG>Name</STRONG> property to <STRONG>Organization</STRONG>.</P>



3.  Replace the **CustTrans** table with the **CustTransExt** view in **CustCube** perspective.
    
    1.  In the AOT, expand **Data Dictionary** and then expand the **Perspectives** node.
    
    2.  Expand the **CustCube** perspective, and then the **Tables** node.
    
    3.  Select the **CustTrans** table and note the values for the following properties: **AnalysisDimensionType**, **AnalysisDimensionLabel**, **AnalysisMeasureGroupLabel**.
    
    4.  Expand the **CustTrans** table and then **Fields**. Note the values for the following properties: **AnalysisLabel**, **AnalysisUsage**, **AnalysisDefaultTotal**, **ExchangeRateDateField**.
    
    5.  Remove the **CustTrans** table from the view.
    
    6.  Drag and drop the **CustTransExt** view under **Views**.
    
    7.  In the **Properties** window, specify the following values. (These values were noted in step **c** above.)
        
        <table>
        <colgroup>
        <col style="width: 50%" />
        <col style="width: 50%" />
        </colgroup>
        <thead>
        <tr class="header">
        <th><p>Property</p></th>
        <th><p>Value</p></th>
        </tr>
        </thead>
        <tbody>
        <tr class="odd">
        <td><p>AnalysisDimensionType</p></td>
        <td><p>Transaction</p></td>
        </tr>
        <tr class="even">
        <td><p>AnalysisDimensionLabel</p></td>
        <td><p>@SYS618</p></td>
        </tr>
        <tr class="odd">
        <td><p>AnalysisMeasureGroupLabel</p></td>
        <td><p>@SYS9305</p></td>
        </tr>
        </tbody>
        </table>
    
    8.  Specify the following properties on fields in the view. (These values were noted in step **d** above.)
        
        <table>
        <colgroup>
        <col style="width: 20%" />
        <col style="width: 20%" />
        <col style="width: 20%" />
        <col style="width: 20%" />
        <col style="width: 20%" />
        </colgroup>
        <thead>
        <tr class="header">
        <th><p>Field</p></th>
        <th><p>AnalysisLabel</p></th>
        <th><p>AnalysisUsage</p></th>
        <th><p>AnalysisDefaultTotal</p></th>
        <th><p>ExchangeRateDateField</p></th>
        </tr>
        </thead>
        <tbody>
        <tr class="odd">
        <td><p>AccountNum</p></td>
        <td><p>-</p></td>
        <td><p>Auto</p></td>
        <td><p>Auto</p></td>
        <td><p>-</p></td>
        </tr>
        <tr class="even">
        <td><p>TransDate</p></td>
        <td><p>-</p></td>
        <td><p>Attribute</p></td>
        <td><p>Auto</p></td>
        <td><p>-</p></td>
        </tr>
        <tr class="odd">
        <td><p>AmountCur</p></td>
        <td><p>@SYS317640</p></td>
        <td><p>Measure</p></td>
        <td><p>Sum</p></td>
        <td><p>-</p></td>
        </tr>
        <tr class="even">
        <td><p>SettleAmountCur</p></td>
        <td><p>@SYS317641</p></td>
        <td><p>Measure</p></td>
        <td><p>Sum</p></td>
        <td><p>-</p></td>
        </tr>
        <tr class="odd">
        <td><p>AmountMST</p></td>
        <td><p>@SYS317642</p></td>
        <td><p>Measure</p></td>
        <td><p>Sum</p></td>
        <td><p>TransDate</p></td>
        </tr>
        <tr class="even">
        <td><p>SettleAmountMST</p></td>
        <td><p>@SYS317643</p></td>
        <td><p>Measure</p></td>
        <td><p>Sum</p></td>
        <td><p>TransDate</p></td>
        </tr>
        <tr class="odd">
        <td><p>CurrencyCode</p></td>
        <td><p>-</p></td>
        <td><p>Auto</p></td>
        <td><p>Auto</p></td>
        <td><p>-</p></td>
        </tr>
        <tr class="even">
        <td><p>DueDate</p></td>
        <td><p>-</p></td>
        <td><p>Attribute</p></td>
        <td><p>Auto</p></td>
        <td><p>-</p></td>
        </tr>
        <tr class="odd">
        <td><p>LastSettleDate</p></td>
        <td><p>-</p></td>
        <td><p>Attribute</p></td>
        <td><p>Auto</p></td>
        <td><p>-</p></td>
        </tr>
        <tr class="even">
        <td><p>Closed</p></td>
        <td><p>-</p></td>
        <td><p>Attribute</p></td>
        <td><p>Auto</p></td>
        <td><p>-</p></td>
        </tr>
        <tr class="odd">
        <td><p>TransType</p></td>
        <td><p>-</p></td>
        <td><p>Attribute</p></td>
        <td><p>Auto</p></td>
        <td><p>-</p></td>
        </tr>
        <tr class="even">
        <td><p>Approved</p></td>
        <td><p>-</p></td>
        <td><p>Attribute</p></td>
        <td><p>Auto</p></td>
        <td><p>-</p></td>
        </tr>
        <tr class="odd">
        <td><p>DocumentDate</p></td>
        <td><p>-</p></td>
        <td><p>Attribute</p></td>
        <td><p>Auto</p></td>
        <td><p>-</p></td>
        </tr>
        <tr class="even">
        <td><p>PaymMode</p></td>
        <td><p>-</p></td>
        <td><p>Auto</p></td>
        <td><p>Auto</p></td>
        <td><p>-</p></td>
        </tr>
        <tr class="odd">
        <td><p>DefaultDimension</p></td>
        <td><p>-</p></td>
        <td><p>Attribute</p></td>
        <td><p>Auto</p></td>
        <td><p>-</p></td>
        </tr>
        <tr class="even">
        <td><p>CustBillingClassification</p></td>
        <td><p>-</p></td>
        <td><p>Auto</p></td>
        <td><p>Auto</p></td>
        <td><p>-</p></td>
        </tr>
        <tr class="odd">
        <td><p>Organization</p></td>
        <td><p>-</p></td>
        <td><p>Auto</p></td>
        <td><p>Auto</p></td>
        <td><p>-</p></td>
        </tr>
        </tbody>
        </table>


## Create the business intelligence project

1.  Click **Tools** \> **Business Intelligence (BI) tools** \> **SQL Server Analysis Services project wizard**. Click **Next**.

2.  Select **Create** and enter the project name. For example, CustCube Hierarchy.

3.  Select **Account receivable cube** and shared dimensions. Then click **Next**.

4.  Select required Microsoft Dynamics AX dimensions. Then click **Next**.

5.  Select calendars for date dimensions. Then click **Next**.

6.  Select required languages. Then click **Next**.

7.  Add foreign currency conversion, if needed. Then click **Next**.

## Edit the business intelligence project in Visual Studio BI

Edit the business intelligence project in Visual Studio BI. You’ll need to:

  - Change Org dimension to a parent-child.

  - Add Org dimenision to the **Dimension usage** of tab of the CustCube cube.

<!-- end list -->

1.  Change **Org** dimension to a parent-child dimension.
    
    1.  Open created project in Visual Studio BI.
    
    2.  Double click **Org** dimension.
    
    3.  Select the **Parent org** member.
    
    4.  In the **Propertise** window, set the **Usage** property to **Parent**.
    
    5.  Process and browse the dimension.

2.  Add the **Org** dimenision to the **Dimension usage** tab of the **CustCube** cube.
    
    1.  In Visual Studio, double-click **CustCube** in Solution Explorer.
    
    2.  Click the **Dimension Usage** tab.
    
    3.  For the **Org** dimension and the **Customer transactions** measure group, click **add relation** and do the following:
        
        1.  Set **Relationship type** to **Regular**.
        
        2.  Set **Granulity attribute** to **Org**.
        
        3.  Set **Dimension Columns** to **RecID**.
        
        4.  Set **Measure Group Columns** to **Organization**.
    
    4.  Process the cube.
    
    5.  Browse the cube.

  



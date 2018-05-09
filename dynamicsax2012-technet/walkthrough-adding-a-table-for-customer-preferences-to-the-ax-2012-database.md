---
title: 'Walkthrough: Adding a table for customer preferences to the AX 2012 database'
TOCTitle: 'Walkthrough: Extending the database schema'
ms:assetid: 2a6f75bf-248c-41ff-a79d-0827255ba531
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn720785(v=AX.60)
ms:contentKeyID: 62231586
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Walkthrough: Adding a table for customer preferences to the AX 2012 database 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

In this walkthrough you create a new table in Microsoft Dynamics AX 2012 to capture additional customer data in a retail channel. The new table is called RetailCustPreferences and it is related to the CustTable so that each customer has the new fields for marketing preferences. You modify the customer form to display and add values to the field in the new table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><img src="images/Dn768211.TopicIcons_Walkthrough(AX.60).png" title="Walkthrough" alt="Walkthrough" />
<p>Prerequisites</p>
<p>Create the RetailCustPreferences table</p>
<p>Add the new fields to the Customer form</p></td>
<td><img src="images/Dn507140.TopicIcons_Resources(AX.60).png" title="Resources" alt="Resources" />
<p><a href="online-store.md">Online Store</a></p>
<p><a href="retail-modern-point-of-sale.md">Retail Modern Point of Sale</a></p></td>
</tr>
</tbody>
</table>


## Prerequisites

These walkthroughs illustrate adding a field to a retail channel that enables customers to opt in to receive special offers by email. In this scenario, the retailer wants to indicate whether customers wish to receive email about special offers, either in an online store or in a modern POS client. The walkthroughs should be completed in the following order:

1.  [Walkthrough: Adding a table for customer preferences to the AX 2012 database](walkthrough-adding-a-table-for-customer-preferences-to-the-ax-2012-database.md)

2.  [Walkthrough: Extending the CRT to add customer preference data for Retail clients](walkthrough-extending-the-crt-to-add-customer-preference-data-for-retail-clients.md)

3.  [Walkthrough: Extending retail data distribution infrastructure for customer preferences](walkthrough-extending-retail-data-distribution-infrastructure-for-customer-preferences.md)

4.  [Walkthrough: Adding customer preferences to the Retail online sample store](walkthrough-adding-customer-preferences-to-the-retail-online-sample-store.md) (online store only)

In the first walkthrough, you create a table to store the customer preferences. The following links provide background information about creating a new table.

  - [How to: Create Tables](https://technet.microsoft.com/en-us/library/aa882181\(v=ax.60\))

  - [Table Properties](https://technet.microsoft.com/en-us/library/aa871620\(v=ax.60\))

  - [Defining Table Relations](https://technet.microsoft.com/en-us/library/bb190076\(v=ax.60\))

  - [How to: Add a Relation to a Table](https://technet.microsoft.com/en-us/library/aa556809\(v=ax.60\))

  - [Best Practices for Table Relations](https://technet.microsoft.com/en-us/library/aa880475\(v=ax.60\))

## Create the RetailCustPreferences table

You use the **Data Dictionary** in the **AOT** to add a new table.

### To add a new table

1.  In the Microsoft Dynamics AX client, press CTRL + D to open the development workspace.

2.  In the AOT, expand **DataDictionary**, right-click the **Tables** node, and then click **New Table**.

3.  Right-click the new table name and then click **Properties**.

4.  Set the **Name** property to **RetailCustPreferences** and then press Ctrl+S to save the new table.

5.  Expand the new **RetailCustPreferences** node, right-click the **Fields** node, click **New**, and then click **Enum**.

6.  Specify the following properties for the new field:
    
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
    <td><p>Name</p></td>
    <td><p>EmailOptIn</p></td>
    </tr>
    <tr class="even">
    <td><p>Label</p></td>
    <td><p>Email Opt In</p></td>
    </tr>
    <tr class="odd">
    <td><p>EnumType</p></td>
    <td><p>NoYes</p></td>
    </tr>
    </tbody>
    </table>


7.  Press Ctrl+S to save your changes.

### To create the relation on the new table

1.  In the AOT, expand the **Data Dictionary** node, expand the **Tables** node and then expand the **RetailCustPreferences** node.

2.  Right-click **Relations** and then click **New Relation**.

3.  Right-click the new relation and then click **Properties**.

4.  Set the values for the properties as shown in the following table.
    
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
    <td><p>Name</p></td>
    <td><p>CustTable</p></td>
    </tr>
    <tr class="even">
    <td><p>Table</p></td>
    <td><p>CustTable</p></td>
    </tr>
    <tr class="odd">
    <td><p>Validate</p></td>
    <td><p>Yes</p></td>
    </tr>
    <tr class="even">
    <td><p>EntityRelationshipRole</p></td>
    <td><p>blank</p></td>
    </tr>
    <tr class="odd">
    <td><p>RelatedTableCardinality</p></td>
    <td><p>ExactlyOne</p></td>
    </tr>
    <tr class="even">
    <td><p>Cardinality</p></td>
    <td><p>ZeroOne</p></td>
    </tr>
    <tr class="odd">
    <td><p>RelationshipType</p></td>
    <td><p>Composition</p></td>
    </tr>
    <tr class="even">
    <td><p>UseDefaultRoleNames</p></td>
    <td><p>Yes</p></td>
    </tr>
    <tr class="odd">
    <td><p>RelatedTableRole</p></td>
    <td><p>blank</p></td>
    </tr>
    <tr class="even">
    <td><p>Role</p></td>
    <td><p>blank</p></td>
    </tr>
    <tr class="odd">
    <td><p>EDTRelation</p></td>
    <td><p>No</p></td>
    </tr>
    </tbody>
    </table>


5.  Right-click the new relation, select **New**, click **ForeignKey**, and then click **PrimaryKey based**.
    
    Notice the **CustTable** field is added for the **RetailCustPreferences** table in the **Fields** node, and the relation is added in the **Relations** node under **CustTable**.

6.  Right-click the new relation under **CustTable** and then click **Properties**.

7.  Set the **SourceEDT** property to **CustAccount**.

8.  Under the **Fields** node, right-click **CustTable** and then click **Properties**.

9.  Set the properties as shown in the following table.
    
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
    <td><p><strong>Name</strong></p></td>
    <td><p>AccountNum</p></td>
    </tr>
    <tr class="even">
    <td><p></p></td>
    <td><p></p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>ExtendedDataType</strong></p></td>
    <td><p>CustAccount</p></td>
    </tr>
    </tbody>
    </table>


10. Right-click **RetailCustPreferences** and then click **Save**.

11. Right-click **RetailCustPreferences** and then click **Sychronize** to apply your changes to the database.

12. Right-click **RetailCustPreferences** and then click **Compile**.

13. To view the contents of the table and add data, you can right-click **ISVCustomerMarketingPreferences** in the **Tables** node, click **Add-Ins**, and then click **Table Browser**.

14. Close the developer workspace and any Microsoft Dynamics AX clients.

## Add the new fields to the Customer form

Adding the fields from the new table to the **Customer** form enables adding data for a test customer by using the Microsoft Dynamics AX client. You add the new table to the **Datasource** node of the **CustTable** form.

### To add a field to the Customer form

1.  Open the Microsoft Dynamics AX developer workspace.

2.  In the AOT, expand the **Forms** node and then expand the **CustTable** node.

3.  Right-click **Data Sources** and then click **New Data Source**.

4.  Right-click the new data source and then click **Properties**.

5.  Set the properties as shown in the following table.
    
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
    <td><p><strong>Name</strong></p></td>
    <td><p>RetailCustPreferences</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Table</strong></p></td>
    <td><p>RetailCustPreferences</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Index</strong></p></td>
    <td><p>blank</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>CounterField</strong></p></td>
    <td><p>blank</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>AllowCheck</strong></p></td>
    <td><p>Yes</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>AllowEdit</strong></p></td>
    <td><p>Yes</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>AllowCreate</strong></p></td>
    <td><p>Yes</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>AllowDelete</strong></p></td>
    <td><p>Yes</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>StartPosition</strong></p></td>
    <td><p>First</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>AutoSearch</strong></p></td>
    <td><p>Yes</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>AutoNotify</strong></p></td>
    <td><p>Yes</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>AutoQuery</strong></p></td>
    <td><p>Yes</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>CrossCompanyAutoQuery</strong></p></td>
    <td><p>No</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>OnlyFetchActive</strong></p></td>
    <td><p>No</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>JoinSource</strong></p></td>
    <td><p>CustTable</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>LinkType</strong></p></td>
    <td><p>OuterJoin</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>DelayActive</strong></p></td>
    <td><p>Yes</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>InsertAtEnd</strong></p></td>
    <td><p>Yes</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>InsertIfEmpty</strong></p></td>
    <td><p>Yes</p></td>
    </tr>
    </tbody>
    </table>


6.  Right-click **CustTable** in the **Forms** node and then click **Save**.

7.  Expand the **Designs** node, the **Design** node, the **Tab:Tab** node, and then the **TabPage:TabPageDetails** node.

8.  Expand the **Tab:TabHeader** node to view the FastTab categories.

9.  Right-click the **TabPage:Retail** node, select **New Control**, and then click **Group**.

10. Set the **Name** property for the new group to **CustomerPreference** and set the **Caption** property to **Customer preferences**.

11. Right-click the **Group:CustomerPreference** node, select **New Control** and then click **CheckBox**. Set the following properties.
    
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
    <td><p>Name</p></td>
    <td><p>RetailCustomerPreferences _EmailOptIn</p></td>
    </tr>
    <tr class="even">
    <td><p>DataSource</p></td>
    <td><p>RetailCustPreferences</p></td>
    </tr>
    <tr class="odd">
    <td><p>DataField</p></td>
    <td><p>EmailOptIn</p></td>
    </tr>
    <tr class="even">
    <td><p>Label</p></td>
    <td><p>Email Opt In</p></td>
    </tr>
    </tbody>
    </table>


12. Right-click **CustTable** in the **Forms** node, click **Save**, and then click **Compile**. You can disregard the Best practices messages.

13. Right-click **CustTable** and then click **Open** to view the form. Click **Edit** on the Action pane.

14. Click **Retail** to open the **Retail** FastTab.

15. Now, we must write code to populate the Customer account.
    
    1.  In the AOT, open the **Forms** node and navigate to the **CustTable** form.
    
    2.  Right-click **CustTable**, click **View Code**.
    
    3.  Click **CustTable:validateWrite**. Add the following line of code to the block before the ret = super(); statement: retailCustPreferences.AccountNum = custTable.AccountNum;.
        
        The following example shows the code block with the new statement.
        
            whsCustTable.AccountNum = custTable.AccountNum;
            if (isConfigurationkeyEnabled(configurationKeyNum(Retail)))
                {
                    retailCustTable.AccountNum = custTable.AccountNum;
                    retailCustPreferences.AccountNum = custTable.AccountNum;
                }
            
            ret = super();

    4.  Click **CustTable:write**. Add the following line of code to the block before the first ttsbegin; statement: retailCustPreferences.AccountNum = custTable.AccountNum;.
        
        The following example shows the code block with the new statement.
        
            if (isConfigurationkeyEnabled(configurationKeyNum(Retail)))
                {
                    retailCustTable.AccountNum = custTable.AccountNum;
                    retailCustPreferences.AccountNum = custTable.AccountNum;
                }
            ttsbegin;

16. Press CTRL+S to save your changes. Close the **Code Editor** window.

17. Right-click the **CustTable** form and then click **Compile**.

18. Restart the AOS.

19. Right-click the **CustTable** form and then click **Open** to view the form. If you have test data loaded, the data shown is for the first customer. Click **Edit** and then open the **Retail** FastTab. Use the **Email Opt In** check box to set the value for a few customers.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


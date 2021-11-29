---
title: 'Walkthrough: Extending retail data distribution infrastructure for customer preferences'
TOCTitle: 'Walkthrough: Extending retail data distribution'
ms:assetid: 9fac92a4-4ad9-47ca-aa25-ae0c95860495
ms:mtpsurl: https://technet.microsoft.com/library/Dn720788(v=AX.60)
ms:contentKeyID: 62231589
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Walkthrough: Extending retail data distribution infrastructure for customer preferences 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

You include the new table fields in the configuration for data distribution to the channel database, the Commerce Runtime (CRT), and the channel. Then you update the schema, and generate classes by using the Microsoft Dynamics AX 2012 client. Next, you create a subjob for the new table to run under the **Customer** job, generate the classes needed, and run the initial data distribution.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><img src="images/Dn768211.TopicIcons_Walkthrough(AX.60).png" title="Walkthrough" alt="Walkthrough" />
<p>Prerequisites</p>
<p>Add the RetailCustPreferences table in the data distribution to the CRT for the Retail channel</p>
<p>Create a subjob</p>
<p>Include the schema of the new table in the Retail scheduler distribution</p></td>
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

## Add the RetailCustPreferences table in the data distribution to the CRT for the Retail channel

The channel schema is the XML description of the data sent from AX 2012 to the channel database.

1.  Open and click **Retail \> Setup \> Retail scheduler \> Retail channel schema**.

2.  Select the schema name that corresponds to the channel. For example, select **AX 2012 R3** for **Name** and then click **Location tables**.

3.  Click **New** and type the name of the new table, **ax.RetailCustPreferences**, in the **Table name** field.

4.  Click **Location Fields** and enter the following field names.
    
    <table>
    <colgroup>
    <col style="width: 33%" />
    <col style="width: 33%" />
    <col style="width: 33%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field name</p></th>
    <th><p>Type</p></th>
    <th><p>Length</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>ACCOUNTNUM</p></td>
    <td><p>None</p></td>
    <td><p>0</p></td>
    </tr>
    <tr class="even">
    <td><p>DATAREAID</p></td>
    <td><p>None</p></td>
    <td><p>0</p></td>
    </tr>
    <tr class="odd">
    <td><p>EMAILOPTIN</p></td>
    <td><p>None</p></td>
    <td><p>0</p></td>
    </tr>
    <tr class="even">
    <td><p>RECID</p></td>
    <td><p>None</p></td>
    <td><p>0</p></td>
    </tr>
    </tbody>
    </table>


5.  Close the **Location fields** and **Location tables** forms.

## Create a subjob

Next, you create a subjob of the CustTable job to move data in the new table to the channel database.

1.  In Retail Headquarters, click **Retail \> Setup \> Retail scheduler \> Scheduler subjobs** and then click **New**.

2.  Enter **RetailCustPreference** in the **Subjob number** and **Description** fields.

3.  Select **AX 2012 R3** for **Retail channel schema**.

4.  Select **ax.RetailCustPreferences** for **Channel table name**.

5.  Select **RetailCustPreferences** for **Microsoft Dynamics AX table name**.

6.  Click **Transfer field list**.

7.  On the **Field list** form, click **Functions** and then click **Match fields**. The **From field** and **To field** columns are filled in.

8.  Click **Ok** on the message dialog to close the **Field list** form.

9.  Open the **Retail channel schema** form (click Retail \> Setup \> Retail scheduler \> Retail channel schema).

10. Copy the XML in the **Table distribution** field into an editor such as Notepad++.
    

    > [!TIP]
    > <P>To copy all the XML, position your cursor and click before the first character (&lt;). Using the scrollbar, scroll to the bottom of the file. Press <STRONG>Shift</STRONG> and then click after the last character (&gt;). This ensures that all the XML is selected.</P>



11. In the XML, search for the line \<Table name = “RetailCustTable”\>. There are two instances, at approximately line 29 and line 744.

12. Add the following code after the final line in both of the \<Table name = “RetailCustTable”\> code blocks. You add the code after the \</Table\> statement.
    
        <Table name="RetailCustPreferences">
                        <LinkGroup>
                          <Link type="FieldMatch" fieldName="accountNum" parentFieldName="AccountNum" />
                        </LinkGroup>
                      </Table>


13. Copy the entire new XML file into the **Table distribution** window on the **Retail channel schema** form.

14. Close the **Retail channel schema** form.

15. Open the **Scheduler job** form (click **Retail** \> **Setup** \> **Retail scheduler** \> **Scheduler job)**.

16. Select **1010** to select the **Customer** job and then selet **RetailCustPreferences** for the subjob.

17. On the **Retail channel Schema** form, select **AX 2012 R3** for the schema name and then click **Generate classes**.
    
    This process may take some time.

## Include the schema of the new table in the Retail scheduler distribution

1.  In Retail Headquarters, click **Retail \> Setup \> Retail scheduler \> Distribution locations**.

2.  Select **OOB Storefront** and then run **Functions \> Read schema**.

3.  Accept the defaults and then click **OK**.

  



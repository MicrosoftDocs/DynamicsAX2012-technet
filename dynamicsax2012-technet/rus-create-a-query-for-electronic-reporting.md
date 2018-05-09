---
title: (RUS) Create a query for electronic reporting
TOCTitle: (RUS) Create a query for electronic reporting
ms:assetid: 5683cf1f-cad1-4e11-8ded-eac9ce26c4a5
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677535(v=AX.60)
ms:contentKeyID: 49384839
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- query
- electronic reporting
- create a query
---

# (RUS) Create a query for electronic reporting 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use the query directory to configure queries to retrieve values from database tables for electronic reporting. You can retrieve values from any database table. Configured queries are used to create values for fixed requisites.

Use the following procedure to create a query for electronic reporting.

1.  Click **General ledger** \> **Setup** \> **Financial reports generator** \> **Queries**.

2.  Click **New**, and then in the **Query** and **Name** fields, enter an identification number and a name for the query.

3.  In the **Query type** field, select the type of query from the following options:
    
      - **Simple** – A query type that you can use to retrieve data from database tables.
    
      - **VAT declaration** – A predefined, customizable query type that uses value-added tax (VAT) transactions.
    
      - **Document requisites** – A query type that uses the requisite that is specified in the **Requisite** field on the **Document requisites** form.

4.  Select the **Create requisites** check box to create requisites in the query directory when you create the query.
    

    > [!NOTE]
    > <P>This check box is available only when you select <STRONG>VAT declaration</STRONG> in the <STRONG>Query type</STRONG> field.</P>



5.  In the **Table** field, select a main query table.
    

    > [!NOTE]
    > <P>This field is available only when you select <STRONG>Simple</STRONG> in the <STRONG>Query type</STRONG> field.</P>



6.  Close the form.

7.  Click **Query** to open the **Inquiry** form, where you can select the required related tables and set limits on field values. For example, if you use the **Electronic documents list** table, the value in the **Document filter** field is set automatically when you upload the document requisites. The identification number for the query document that you create is the value for the filter setting.

8.  Click **OK**.

9.  To reset the query, click **Reset**, and then click **OK**. Click **Query** to open the **Inquiry** form, where you can update the query.

10. Click **Fixed requisites** to open the **Fixed requisites** form, where you can view the requisites with values that are created based on the query.

## See also

[(RUS) Queries (form)](https://technet.microsoft.com/en-us/library/jj710734\(v=ax.60\))

[(RUS) Create query (form)](https://technet.microsoft.com/en-us/library/jj710690\(v=ax.60\))

[(RUS) Fixed requisites (form)](https://technet.microsoft.com/en-us/library/jj710680\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


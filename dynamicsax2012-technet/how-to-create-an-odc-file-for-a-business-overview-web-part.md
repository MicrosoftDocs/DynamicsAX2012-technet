---
title: 'How to: Create an ODC file for a Business Overview Web Part'
TOCTitle: 'How to: Create an ODC file for a Business Overview Web Part'
ms:assetid: 5adb5104-a84f-432b-aed0-6ecc5ce057fb
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh128831(v=AX.60)
ms:contentKeyID: 35588430
ms.date: 11/11/2013
mtps_version: v=AX.60
---

# How to: Create an ODC file for a Business Overview Web Part [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use the Business Overview web part in role centers or Enterprise Portal to display business information such as measures or Key Performance Indicators (KPIs). An Office Data Connection (ODC) file is used to identify the Analysis Services database that contains measures and KPIs. You do not need an ODC file if you use measures or KPIs from the default Analysis Services database that ships with Microsoft Dynamics AX because the Business Overview web part will point to the default Analysis Services database. However, if you create additional Analysis Services databases, you must create ODC files to use measures and KPIs from those databases.

## Deploying an ODC File

To deploy an ODC file, you must create the ODC file by using the Data Connection Wizard in Microsoft Excel and then add the ODC file to Enterprise Portal.

### To create an ODC file

1.  In Excel, click **Data** \> **From Other Sources** \> **From Analysis Services**. The **Data Connection Wizard** is displayed.

2.  On the **Connect to Database Server** page, specify the server that has the Analysis Services database, specify the log on credentials to use for the server, and then click **Next**.

3.  On the **Select Database and Table** page, select the Analysis Services database. Clear the **Connect to a specific cube or table** check box, and then click **Next**.

4.  On the **Save Data Connection File and Finish** page, enter a file name and friendly name, and then click **Finish**. The **Import Data** wizard is displayed.

5.  Click **Properties…**.

6.  On the **Definition** tab, verify that the connection string points to the correct Analysis Services database. Click **Export Connection File…**.

7.  Provide a name for the file. For example, Dynamics AX.odc.

8.  Click **Save** and close Excel.
    

    > [!NOTE]
    > <P>If you want to use user credentials for authorization, you must add the following line to your ODC file:</P>
    > <P>&lt;odc:DynamicsConnectionAccount&gt;AppPoolWithEffectiveUserName&lt;/odc:DynamicsConnectionAccount&gt;</P>



### To add the ODC file to Enterprise Portal

1.  Open Enterprise Portal. Be sure that you are accessing the main Enterprise Portal site. From the **Site Actions** menu, click **New Document Library**.

2.  In the **Name** field, enter Data Connections.

3.  In the **Navigation** and **Document Version History** sections, select **No**.

4.  In the **Document Template** section, select **None**. Click **Create**.

5.  Click **Add document**.

6.  Click **Browse** and locate the ODC file that you created. For example, ..\\Documents\\My Data Sources\\Dynamics AX.odc. Click **OK**.

When you specify the data connection for a Business Overview web part, use the relative path Data Connections/\<ODCFileName\>. For example, Data Connections/Dynamics AX.odc.

## See also

[Walkthrough: Defining KPIs for a Cube](walkthrough-defining-kpis-for-a-cube.md)

[Web Parts Overview](https://technet.microsoft.com/en-us/library/cc588397\(v=ax.60\))

[Business Overview Web Part](https://technet.microsoft.com/en-us/library/gg862274\(v=ax.60\))


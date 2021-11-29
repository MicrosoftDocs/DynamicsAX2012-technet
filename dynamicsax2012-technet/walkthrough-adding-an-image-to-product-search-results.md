---
title: 'Walkthrough: Adding an Image to Product Search Results'
TOCTitle: 'Walkthrough: Adding an Image to Product Search Results'
ms:assetid: 28fc786f-7315-4e60-b498-f2ce5e20c7c0
ms:mtpsurl: https://technet.microsoft.com/library/JJ937971(v=AX.60)
ms:contentKeyID: 50950763
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Walkthrough: Adding an Image to Product Search Results 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In this walkthrough, you will customize Microsoft Dynamics AX for Retail POS by adding images to items displayed during a product search. As part of this customization, you will learn:


> [!TIP]
> <P>This topic applies to Microsoft Dynamics AX 2012 Feature Pack. This functionality is already included in Microsoft Dynamics AX 2012 R2.</P>



  - How to add new data to sych between Microsoft Dynamics AX for Retail Headquarters and Retail POS.

  - How to enable change tracking on a Retail Headquarters database table.

  - How to create a new form in Retail POS to display the data.

In this example, you will add product images from Retail Headquarters by customizing the **frmItemSearch.cs** form in Retail POS, resulting in a new form called **frmItemDetails.cs**.

## Prerequisites

To customize a form in Retail POS, you must obtain a license from [DevExpress](http://www.devexpress.com/). Retail POS uses DXExperience Winforms created by DevExpress. You can develop your own forms without using DevExpress, but we recommend you use these to maintain a consistent appearance and behavior.This tutorial is based on the Microsoft Dynamics AX 2012 Contoso dataset and uses ‘CEU’ as its default company. If you use your own data, you will need to make changes based on your organization’s structure.

### ![JJ937971.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ937971.collapse_all(en-us,AX.60).gif")Steps in this walkthrough

The following sections will walk you through the steps that are required for you to complete this tutorial:

  - Define an archive directory for document handling

  - Enable Retail change tracking on EcoResProductImage table

  - Create the EcoResProductImage table in Retail POS

  - Define table distribution data for the EcoResProductImage table

  - Add an image to a product and synch data

  - Create a form to display an image with the searched product

  - Configure a Blank Operation on Retail POS register

### ![JJ937971.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ937971.collapse_all(en-us,AX.60).gif")Define an archive for document handling

The following step is a requirement of Microsoft Dynamics AX 2012’s **Document Management** system. For more information on **Document Management** in Microsoft Dynamics AX 2012, see [Using document management](using-document-management.md).

1.  Launch Microsoft Dynamics AX for Retail Headquarters.

2.  Click **Organization Administration \> Setup \> Document management \> Document management parameters**.

3.  Set a value in the **Archive** directory field on the **General** page, for example, \<rootdirectory\>:\\temp.

### ![JJ937971.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ937971.collapse_all(en-us,AX.60).gif")Make images available in offline mode

In online mode Retail Modern POS retrieves images for products, customers, catalogs and categories from an image server using the specified URL. To support images in offline mode you can configure a default image using the document management functionality in Microsoft Dynamics AX 2012. Document management must be configured to use the active document tables. The images are then stored in the AX 2012 business database and are synced to the channel database and subsequently to the offline database.

For more information, see [Configure document management](configure-document-management.md).

1.  Click **Organization administration** \> **Setup** \> **Document management** \> **Document types**.

2.  Enter **RetailImage** for the **Type**, set the **Class** to **Attach file**, and the location to **Archive directory**.

![Retail Modern POS Offline Image Document Type](images/JJ937971.RetailModernPOSOfflineImageType(en-us,AX.60).png "Retail Modern POS Offline Image Document Type")

To attach an image when in offline mode, use the **Attachment** button in the ribbon of the appropriate form.

### ![JJ937971.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ937971.collapse_all(en-us,AX.60).gif")Enable Retail change tracking on EcoResProductImage table

Change tracking is a way for Retail Headquarters and Retail POS to maintain data synchronization. For example, any changes made to a table in Retail Headquarters will be pushed out to the appropriate Retail POS channels via scheduler jobs. Scheduler jobs are explained later in this topic. In this section, you will use the EcoResProductImage table, which is part of the core Microsoft Dynamics AX 2012 product. Below, you will add update, delete and insert methods. These methods are used to modify the table and trigger change tracking. Alternatively, you could create your own table. Follow these steps:

1.  Open the Microsoft Dynamics AX Application Object Tree (AOT).

2.  Expand the **Data Dictionary \> Tables** node.

3.  Right-click the **EcosResProductImage** table and then click **View Code**.

4.  Create a new method named delete. For more information about how to create methods, see [Methods in X++](https://msdn.microsoft.com/library/aa673265).

5.  Insert the following code into the new method:
    
        /// <summary>
        /// Deletes a record in <c>EcoResProductImage</c> table. Added as part of Retail POS development tutorial.
        /// </summary>
        /// <remarks>
        /// If replication of the record is allowed for the table, action is inserted into the <c>RetailConnPreactionTable</c> table.
        /// </remarks>
        public void delete()
        {
        
            Boolean replicate = false;
        ;
            replicate = RetailConnActionManagement::shouldReplicate(this, this.orig(), true);
        
            super();
        
            if (replicate)
            {
                RetailConnActionManagement::createActions(this, RetailConnActionUpdate::Delete);
            }
        }

6.  Create a new method named insert and then add the following code.
    
    ``` 
    /// <summary>
    /// Inserts a record in <c>EcoResProductImage</c> table. Added as part of Retail POS development tutorial. 
    /// </summary>
    /// <remarks>
    /// If replication of the record is allowed for the table, action is inserted into the <c>RetailConnPreactionTable</c> table.
    /// </remarks>
    public void insert()
    {
    
        Boolean replicate = false;
    ;
        replicate = RetailConnActionManagement::shouldReplicate(this, this.orig(), false);
    
        super();
    
        if (replicate)
        {
            RetailConnActionManagement::createActions(this, RetailConnActionUpdate::Insert);
        }
    }
    
    ```

7.  Create a new method named update and then add the following code.
    
    ``` 
    /// <summary>
    /// Updates the record in <c>EcoResProductImage</c> table. Added as part of Retail POS development tutorial.
    /// </summary>
    /// <remarks>
    /// If replication of the record is allowed for the table, action is inserted into the <c>RetailConnPreactionTable</c> table.
    /// </remarks>
    public void update()
    {
    
        Boolean replicate = false;
    ;
        replicate = RetailConnActionManagement::shouldReplicate(this, this.orig(), false);
    
        super();
    
        if (replicate)
        {
            RetailConnActionManagement::createActions(this, RetailConnActionUpdate::Update);
        }
    }
    
    ```
    
    The three new methods enable change tracking on the EcoResProductImage table. Any update, delete or insert actions on that table with signal that data has changed.

### ![JJ937971.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ937971.collapse_all(en-us,AX.60).gif")Create the EcoResProductImage table in Retail POS

In this section, you will create a new table in Retail POS and then copy data from Microsoft Dynamics AX 2012 to the new table. This data consists of the image that you added to a product in the previous section.

### Create the new table

1.  Open Microsoft SQL Server Management Studio.

2.  In **Object Explorer**, expand the database node for Microsoft Dynamics AX 2012 and then expand the **Tables** node.

3.  Scroll down to the **EcoResProductImages** table. Right-click the table, point to **Script table as**, then point to **CREATE to**, and then click **New Query Editor Window**.

4.  Go to the top line of the generated script and change the USE statement to the name of the Retail POS database. The default name for this database is **AxRetailPOS**. In this case, the statement would be changed to USE \[AxRetailPOS\] in the first line of the generated script.

5.  Click **Execute** or press **F5** to run the script.

### Read the schema of the new table in Retail POS

1.  In Retail Headquarters, click **Retail \> Setup \> Retail scheduler \> Distribution locations**.

2.  Select **Store 1** and then run **Functions \> Read schema**.

3.  Accept the defaults and then click **OK**.

By reading the schema, Microsoft Dynamics AX 2012 is now aware of the new table in Retail POS.

### ![JJ937971.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ937971.collapse_all(en-us,AX.60).gif")Define table distribution data for the EcoResProductImage table

You must now create table distributions for use with **A-jobs**. Data is transferred between Retail Headquarters and Retail POS through Commerce Data Exchange: Synch Service. This service uses Ax Scheduler jobs in Retail Headquartersto handle this data transfer. The table distribution tree in Retail Headquarters defines what data is transferred to specific retail channels. For instance, if a product is available only at specific stores, that product’s image will be sent only to those stores.

There are two types of AX Scheduler jobs created when Retail is initialized. **A-Jobs** use change-tracking, which means they only transfer data that has been changed. **N-Jobs** transfer all of the data in a table. This includes data that has not been modified.

Usually, you will use **A-Jobs** for ongoing data transfers.

1.  Open **Retail \> Setup \> Retail scheduler \>Table distribution**.

2.  Open **RetailConnDistributionLocation \> RetailStoreTable \> RetailChannelTable \> RetailAssortmentExploded \> RetailInventTable \> InventTable**.

3.  Click **New**.

4.  In the **Details** area, click the **Table ID** drop-down list and then select the **EcoResProductImage** table.
    

    > [!NOTE]
    > <P>It can take some time to load data into this list.</P>



5.  In the navigation tree, select the table distribution that you created in the previous step.. For example, the following image shows the table distribution tree for the **EcoResProductImage** table.
    
    ![Table Distribution form](images/JJ937971.TableDistribution(en-us,AX.60).png "Table Distribution form")

6.  Click **Table links**.

7.  Enter a link number and then expand the **Line Details** FastTab.

8.  In the **Field name** drop-down list, select **RecID** and in the **Parent** field select **Product**, as shown in the following image.
    
    ![Table Distribution Link ID](images/JJ937971.TableDistributionLinkID(en-us,AX.60).png "Table Distribution Link ID")

9.  Close the **Table distribution** form.

10. Update the Distribution schedules. Click **Retail \> Setup \> Retail scheduler \> Scheduler subjobs**.

11. Create a new **scheduler subjob**. Call it BDDP-ProdImage.

12. Select **AX6.2 POS** in the **Retail channel schema** drop-down list.

13. Type EcoResProductImage in both the **Channel table name** and **AX table name** fields, as shown in the following image.
    
    ![Scheduler Subjob](images/JJ937971.SchedulerSubJob(en-us,AX.60).png "Scheduler Subjob")

14. For the **Replication method**, select **By actions**.

15. Click the **Transfer field list** button.

16. Click the **Functions \> Match Fields** button in the new window that opens. An infolog message will tell you that all fields are matched. Click **OK** to close the window.

17. Close the **Scheduler subjobs** form.

18. Click **Retail \> Setup \> Retail scheduler \> Scheduler job**.

19. Add the new sub-job, named **BDDP-ProdImage**, to the **A-1040** scheduler job, as shown in the following image.
    
    ![Scheduler Job](images/JJ937971.TableDistributionSchedulerJob(en-us,AX.60).png "Scheduler Job")

### ![JJ937971.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ937971.collapse_all(en-us,AX.60).gif")Add an image to a product and synch data

In this section, you will use Retail Headquarters to select images and attach them to their respective product. You will then synch this newly associated data to Retail POS using the sub-job created in the previous section.

1.  Click **Retail \> Common \> Products \> Released products by category**

2.  Click the **Product image** button.

3.  Click **New**.

4.  In the **Type** drop-down list, select **Image** and then browse to an image directory where your images are stored For example, browse to \<rootdirectory\>:\\images.
    

    > [!TIP]
    > <P>You can see the image that you added to the product directly on the <STRONG>Released product details</STRONG> form if you double-click the product name.</P>



5.  Click **Retail \> Periodic \> Data distribution \> Create actions**.

6.  Accept the default values in the **Mastering job for converting pre-actions to actions** form and then click **OK**.

7.  Open the **A-1040 distribution schedule** (**Retail \> Periodic \> Retail scheduler \> Distribution schedule**). Select **A-1040** from the list and then click **Run directly**.
    

    > [!WARNING]
    > <P>You can use the following SQL script to verify that your product images were transferred from Microsoft Dynamics AX 2012 to Retail POS. If you need to, you can substitute the organization names in this script with those of your Microsoft Dynamics AX 2012 client in the DATAAREAID clauses and the ITEMID numbers of the products you chose to add images to.</P>



<!-- end list -->

    --select RECID, * from inventtable where ITEMID in ('0001', '0002', '0003') and DATAAREAID = 'ceu'
    
    -- This statement returns the image records for retail products 0001, 0002 and 0003.
    select REFRECORD, REFRECID, * from ECORESPRODUCTIMAGE 
    where REFRECORD in (
    select RECID from inventtable where ITEMID in ('0001', '0002', '0003') and DATAAREAID = 'ceu')
    
    --select COUNT(*) from ECORESPRODUCTIMAGE
    
    
    --SELECT THUMBNAILSIZE, MEDIUMSIZE FROM ECORESPRODUCTIMAGE WHERE REFRECORD = 
    --  (select RECID from inventtable where ITEMID = '0001' and DATAAREAID = 'ceu')
    --   ORDER BY REFRECORD

### ![JJ937971.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ937971.collapse_all(en-us,AX.60).gif")Create a form to display an image with the searched product

1.  Launch Visual Studio 2008 or 2010
    
    In the **File** menu, click **New Project**. Under **Visual C\#** select **Class Library**. Name the project ItemDetails. Ensure that the **Create directory for solution** check box is selected and then click **OK**.

2.  Navigate to the directory that contains Microsoft Dynamics AX for Retail POS Plug-ins. For more information about how to install Retail POS, see [Install the Retail SDK](install-retail-sdk-retail-pos-plug-ins.md). Open the **Services** folder.

3.  Copy the **Blank Operations** and **Dialog** folders to the directory that contains your Visual Studio solution named ItemDetails.

4.  Add the **BlankOperations.csproj** and **Dialog.csproj** files to your Visual Studio **ItemDetails** solution. For more information about how to add existing projects to Visual Studio solutions, see [How to add an existing project to a solution (Visual Studio)](https://msdn.microsoft.com/library/aa179467\(v=sql.80\).aspx)

5.  In **Solution Explorer**, expand the **Dialog** project and then expand the **WinFormsTouch** node. Right-click the **frmItemSearch.cs** file and then select **Copy**. Navigate back to the **WinFormsTouch** node, right-click and select **Paste**.
    
    You will now have a new file under the **WinFormsTouch** node called **Copy of frmItemSearch.cs**. Right-click that file, select **Rename** and change its name to **frmItemDetails.cs**.

6.  Right-click the **frmItemDetails.cs** file and then select **View Code**. Add the following two using statements at the top of the file, if they are not already there:
    
    using LSRetailPosis.DataAccess;
    
    using LSRetailPosis.DataAccess.DataUtil;

7.  Because you copied the frmItemSearch.cs file, you have to make some modifications to the frmItemDetails.cs file, or the code will not compile. First, in frmItemDetails.cs, rename the class from public class frmItemSearch : frmTouchBase to public class frmItemDetails : frmTouchBase.
    
    Change the name of the default class constructor from frmItemSearch to frmItemDetails.
    
    Change the name of the overloaded class constructor from frmItemSearch(int howManyRows) to rmItemDetails(int howManyRows).

8.  The following method will find, format and display an image next to a searched product if an image is found.
    
        public void LoadPictureFromDB(string itemId)
                {
                    //clear the current picture
                    itemPicture.Image = null;
                    
                    try
                    {
                        DBUtil dbUtil = new DBUtil(Dialog.InternalApplication.Settings.Database.Connection);
                       
                        string sql = "SELECT THUMBNAILSIZE, MEDIUMSIZE FROM ECORESPRODUCTIMAGE WHERE REFRECORD = (select RECID from inventtable where ITEMID = @ITEMID and DATAAREAID = @DATAAREAID) ORDER BY REFRECORD";
                        
                        if (itemId == null)
                        {
                            
                            if (grdView.RowCount > 0)
                            {
                                System.Data.DataRow Row = grdView.GetDataRow(grdView.GetSelectedRows()[0]);
                                itemId = (string)Row[colItemId.FieldName];
                               
                            }
                        }
        
                    
        
                        DataTable dt = dbUtil.GetTable(sql, new SqlParameter("@ITEMID", itemId),new SqlParameter("@DATAAREAID", ApplicationSettings.Database.DATAAREAID));
                        byte[] pictureData = (byte[])dt.Rows[0]["MEDIUMSIZE"];
        
                        if (pictureData.Length > 0)
                        {
                            Image i = LSRetailPosis.ButtonGrid.GUIHelper.GetBitmap(pictureData);
                            itemPicture.Height = i.Height;
                            itemPicture.Width = i.Width;
                            itemPicture.Top = (itemPicture.Parent.Height - itemPicture.Height)/2;
                            itemPicture.Left = (itemPicture.Parent.Width - itemPicture.Width) / 2;
                            itemPicture.Image = LSRetailPosis.ButtonGrid.GUIHelper.GetBitmap(pictureData);
                            
                        }
        
                        
                    }
                    catch (Exception ex)
                    {
                        LSRetailPosis.ApplicationExceptionHandler.HandleException(ex.Message, ex);
                    }
                }

9.  Double-click the **frmItemDetails.cs** file to open it in the **Designer**.

10. Click **Run Designer** near the bottom of the form.

11. Click the **Columns** button and then select **colItemName**. Set its **Width** property to **120**.
    
    Select the **colItemID**. Set its **Width** property to **300**.
    
    ![Set column widths](images/JJ937971.Setcolumnwidths(en-us,AX.60).png "Set column widths")

12. Close the **Property editor** window.

13. On the upper-left side of Visual Studio, expand the **Toolbox** and select **PictureBox**. Drag and drop the **PictureBox** to the right-side of the **ItemDetails.cs** form.
    
    ![Add Picture Box](images/JJ937971.AddPictureBox(en-us,AX.60).png "Add Picture Box")
    
    Use the **Designer** to expand the **PictureBox** so that it aligns with the rest of the form. In the **Properties** window, change the **Name** of the control from pictureBox1 to itemPicture.

14. Save your changes.

15. Compile the **Dialog** project.

### Add your custom logic to the Blank Operation

1.  In **Solution Explorer**, expand the **BlankOperations** project and then double-click the **BlankOperations.cs** file to open it.

2.  Add a reference to the **Dialog** project. To add the reference, browse to the Dialog.dll, which is typically located in the bin\\debug folder of the **Dialog** folder where you installed Retail POS Plug-ins.

3.  Double-click the **BlankOperation.cs** file to open it.

4.  Several Blank Operations can be passed to Retail POS simultaneously. Use a C\# Switch statement on the operationInfo.OperationId value to capture the specific one you need. The operationInfo.OperationId value will match the **Operation number** of the **Blank Operation** button on the Retail POS register, which you will set in the next section. In the following C\# code example, set the value to ItemDetails and add the remaining code to the BlankOperation method:
    
    ``` 
    
            public void BlankOperation(IBlankOperationInfo operationInfo, IPosTransaction posTransaction)
            {
                switch (operationInfo.OperationId) 
                {
                    case "ItemDetails":
                        
                        
                        
                        using (Dialog.WinFormsTouch.frmItemDetails frmItemDetails = new Dialog.WinFormsTouch.frmItemDetails(500))
                        {
                            //Display new Item details form
                            
                            DialogResult dr = frmItemDetails.ShowDialog();
                            string selectedItemID = frmItemDetails.SelectedItemId;
                            if (dr == DialogResult.OK)
                            {
                                Application.RunOperation(PosisOperations.ItemSale, selectedItemID);
                            }          
    
                        }
    
                    break;
    
                    default: ….ETC…
    
    
                      NOTE: The following is boilerplate code that can be removed
                        StringBuilder comment = new StringBuilder(128);
                        comment.AppendFormat(ApplicationLocalizer.Language.Translate(50700), operationInfo.OperationId);
                        comment.AppendLine();
                        comment.AppendFormat(ApplicationLocalizer.Language.Translate(50701), operationInfo.Parameter);
                        comment.AppendLine();
                        comment.Append(ApplicationLocalizer.Language.Translate(50702));
                
                        using (LSRetailPosis.POSProcesses.frmMessage dialog = new LSRetailPosis.POSProcesses.frmMessage(comment.ToString(), MessageBoxButtons.OK, MessageBoxIcon.Error))
                        {
                            LSRetailPosis.POSProcesses.POSFormsManager.ShowPOSForm(dialog);
                        }
                        break;
    
                }
    ```

5.  Right-click the **BlankOperation** project and then click **Build**. The BlankOperation.dll and Dialog.dll will both be compiled. These output files will typically be located under the bin\\debug folder of the **BlankOperations** folder where you installed Retail POS Plug-ins.

6.  Copy the BlankOperations.dll and the Dialog.dll to the Retail POS runtime, which is typically located at the \<root\>\\Program Files (x86)\\Microsoft Dynamics AX\\60\\Retail POS.
    

    > [!WARNING]
    > <P>We recommend that you back up the original BlankOperations.dll and Dialog.dll in the Retail POS runtime folder before you add your customized assemblies.</P>



### ![JJ937971.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ937971.collapse_all(en-us,AX.60).gif")Configure a Blank Operation on the Retail POS register

1.  Launch Retail POS and right-click on a blank button. For more information about how to set up Blank Operations, see [Use BlankOperations to implement custom features](use-blankoperations-to-implement-custom-features.md).
    

    > [!WARNING]
    > <P>The following steps represent a temporary configuration of a Retail POS button. Any register updates that are pushed down from Microsoft Dynamics AX for Retail Headquarters will eliminate this configuration. To configure this button in Retail Headquarters, see <A href="setting-up-screen-layouts.md">Setting up screen layouts</A></P>



2.  Select **Button properties**. The **Configure button** form opens.

3.  In the **Action** drop-down menu, click **Blank Operation**.

4.  In the **Operation number** field, type ItemDetails (the value is case-sensitive). Retail POS uses this value to identify which BlankOperation to run, if more than one is sent.

5.  Optionally, you can change the text display on the button to something other than **Blank Operation**.

6.  Click **OK** to close the form.

7.  Click the button you just configured.

8.  Select or type the **Item Number** of the product to which you added an image, and then click the **Search** icon. You should see something similar to the following image:
    
    ![ImageDisplayedWithItem](images/JJ937971.ImageDisplayedWithItem(en-us,AX.60).png "ImageDisplayedWithItem")

  



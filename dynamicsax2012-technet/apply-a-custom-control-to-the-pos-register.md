---
title: Apply a custom control to the POS register
TOCTitle: Apply a custom control to the POS register
ms:assetid: ab80594f-e86e-48b5-b325-923ce081aee6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn741453(v=AX.60)
ms:contentKeyID: 62219730
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Apply a custom control to the POS register [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

You can enhance or change the information displayed on the Microsoft Dynamics AX for Retail POS register by adding custom controls. You implement custom controls using the Microsoft Dynamics AX for Retail POS Plug-ins. For more information about how to install Retail POS Plug-ins, see [Install the Retail SDK](install-retail-sdk-retail-pos-plug-ins.md).

In the following example, the name of the cashier logged into the Retail POS register is displayed at the top of the register form. In addition, the number of line items for the current transaction is displayed below the cashier’s name.

## Create a custom control in Microsoft Dynamics AX for Retail Headquarters

When you create a custom control on the Retail POS register, you must do the following:

  - Create a localized **Caption text ID** in the Retail Headquarters database.

  - Define the custom control in the Retail Headquarters **Custom fields** form.

  - Add the custom control to the Retail Headquarters **Screen layouts** form.

  - Implement the custom control in a plug-in assembly.

### To create a localized Caption text ID

1.  In Retail Headquarters, open a **New Development Workspace**.

2.  Expand the **Data Dictionary** node.

3.  Expand the **Tables** node.

4.  Right-click and then click **Open** for the **RetailLanguageText** table.

5.  Press Ctrl+N to create a new record.

6.  Add the following values for the fields listed:
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Value</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>languageId</p></td>
    <td><p>en-US</p></td>
    </tr>
    <tr class="even">
    <td><p>Text</p></td>
    <td><p>CustomControl1</p></td>
    </tr>
    <tr class="odd">
    <td><p>TextId</p></td>
    <td><p>1001</p></td>
    </tr>
    </tbody>
    </table>
    
    The value in the **Text** field is displayed on the custom control at design time. If the string is not localized, the value will not display correctly.

7.  Close the table to save your changes.

8.  Close the development workspace.

### To define the custom control

1.  In Retail Headquarters, click **Retail \> Setup \> POS \> Profiles \> Custom fields**.

2.  Click **New**.

3.  Set the **Name** field to CustomControl1 and the **Caption text ID** field to 1001.

4.  Set the **Type** field to **Custom control**.

5.  Close the form.

### To add the custom control to the Screen layouts form

1.  Click **Retail \> Setup \> POS \> Screen layouts**.

2.  Click **Designer**.

3.  Click the **Design mode** dropdown list and then select **Main layout**.

4.  From the **Customization** list, click CustomControl1 and drag it to the top of the **Main layout** section of the form.
    
    ![Custom Control](images/Dn741453.POSCustomControl1(en-us,AX.60).png "Custom Control")

5.  Click **OK** to close the form.

6.  Close the **Screen layouts** form.

7.  Click **Retail \> Periodic \> Data distribution \> Distribution schedule** .

8.  From the **Name** list, select **N-1090** and then click the **Run directly** button at the top of the form. This runs a job to synch your changes to the Retail POS register.

9.  Close the form.

### To implement the control in a plug-in assembly

1.  Launch Visual Studio 2008 or 2010.

2.  From the **File** menu, click **New Project**. Under **Visual C\#** select **Class Library**. Name the project POSCustomControl. Ensure that the **Create directory for solution** check box is selected and then click **OK**.

3.  Add a reference to the Microsoft.Dynamics.Retail.Pos.Contracts.dll by right-clicking the **References** node, clicking **Add Reference** and browsing to the location of the POS Plug-ins folder of the Retail SDK.
    

    > [!WARNING]
    > <P>You must set the <STRONG>Embed Intertop Types</STRONG> property to True on the Microsoft.Dynamics.Retail.Pos.Contracts.dll in order to open a Retail POS register.</P>



4.  Add a reference to the Transaction.dll by right-clicking the **References** node, clicking **Add Reference** and browsing to the location of the Retail POS runtime, which is typically located at \<root\>\\Program Files (x86)\\Microsoft Dynamics AX\\60\\Retail POS.

5.  Add a reference to the System.ComponentModel.Composition.dll by right-clicking the **References** node, clicking **Add Reference** and then selecting it from the **Framework \> Assemblies** list.

6.  Right-click the **POSCustomControl** project node and then click **Add \> User Control** from the context menu.

7.  Name the user control **CustomControl1.cs** to match the name of the custom field you created in Retail Headquarters.

8.  Using the **Toolbox**, drag three **Labels** to **CustomControl1.cs**.

9.  Add the following values:
    
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
    <th><p>Label</p></th>
    <th><p>Property</p></th>
    <th><p>Value</p></th>
    <th><p>Property</p></th>
    <th><p>Value</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>Label 1</p></td>
    <td><p>Name</p></td>
    <td><p>lblWorker</p></td>
    <td><p>Text</p></td>
    <td><p>Worker:</p></td>
    </tr>
    <tr class="even">
    <td><p>Label 2</p></td>
    <td><p>Name</p></td>
    <td><p>lblWorkerName</p></td>
    <td><p>Text</p></td>
    <td><p>&lt;blank&gt;</p></td>
    </tr>
    <tr class="odd">
    <td><p>Label 3</p></td>
    <td><p>Name</p></td>
    <td><p>lblItemCount</p></td>
    <td><p>Text</p></td>
    <td><p>&lt;blank&gt;</p></td>
    </tr>
    </tbody>
    </table>
    
    The text fields for lblWorkerName and lblItemCount are filled in dynamically depending on the name of the logged-in cashier and the number of line items on the current transaction.

10. Right-click the CustomControl1.cs file, click **View Code** and add the following using statements.
    
    ``` 
    using LSRetailPosis.Transaction;
    using Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity;
    using Microsoft.Dynamics.Retail.Pos.Contracts.UI;
    using System.ComponentModel.Composition;
    
    ```

11. Add the following code to your CustomControl1 class.
    
    ``` 
    namespace POSCustomControl
    {
        [Export(typeof(IPosCustomControl))]
        [PartCreationPolicy(CreationPolicy.NonShared)]
        public partial class UserControl1 : UserControl, IPosCustomControl
        {
            public UserControl1()
            {
                InitializeComponent();
            }
            /// <summary>
            /// Method is called when transactions changes.
            /// </summary>
            /// <param name="transaction">The transaction.</param>
            public void TransactionChanged(IPosTransaction transaction)
            {
                RetailTransaction retailTransaction = transaction as RetailTransaction;
    
                // Display the item count of the transaction in the label
                lblItemCount.Text = string.Format("Sale line(s) count : {0}", retailTransaction == null ? 0 : retailTransaction.SaleItems.Count);
    
    
                if (retailTransaction != null)
                {
                    // If the transaction item count is greater than 2 then make the label red
                    if (retailTransaction.SaleItems.Count > 2)
                    {
                        lblItemCount.ForeColor = Color.Red;
                    }
                }
                else
                {
                    lblItemCount.ForeColor = Color.Black;
                }
            }
    
            /// <summary>
            /// Load layout.
            /// </summary>
            /// <remarks>Called when new layout is being loaded. e.g. during operator log on.</remarks>
            public void LoadLayout(string layoutId)
            {
                // Display the Cashier's name on the custom control
                lblWorkerName.Text = LSRetailPosis.Settings.ApplicationSettings.Terminal.TerminalOperator.Name;
            }
        }
    }
    
    ```

12. Right-click the **POSCustomControl** project node and then click **Build**.

13. Copy the POSCustomControl.dll to the Extensions folder of the Retail POS runtime, which is typically located under \<root\>\\Program Files (x86)\\Microsoft Dynamics AX\\60\\Retail POS\\Services.

14. Start Retail POS and add three line items to a sales transaction. You should see something similar to the following:
    
    ![Custom field on POS form](images/Dn741453.POSCustomField_End(en-us,AX.60).png "Custom field on POS form")

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


---
title: Use BlankOperations to implement custom features
TOCTitle: Use BlankOperations to implement custom features
ms:assetid: 1ba88c7c-ba82-4d38-9b96-91f04bc06a83
ms:mtpsurl: https://technet.microsoft.com/library/JJ937970(v=AX.60)
ms:contentKeyID: 50950758
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Use BlankOperations to implement custom features 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Blank Operations enable you to extend Microsoft Dynamics AX for Retail POS by adding custom logic to the Retail POS register buttons. The Retail POS register includes at least one blank button under each menu item that you can use to add new functionality. For example, if you launch Retail POS and click the **Cashier Tasks** button, you see a blank button. You can use this button to add new functionality to the other options in cashier tasks.

Although the number of blank buttons is limited, there is no limit to the number of Blank Operations you can deploy because Blank Operations can be applied to any button on the Retail POS register.

### Setting up a Blank Operation on the Retail POS register

1.  Launch Retail POS, right-click the **Cashier Tasks** button and select **Button Properties**. The **Configure button** form opens.

2.  In the **Action** drop-down list box, select **Blank Operation**. The **Operation number** field is a string value that Retail POS uses to identify your Blank Operation. Because you can send multiple blank operations to Retail POS simultaneously, you must give each one a unique identity for Retail POS to distinguish which ones to execute.
    

    > [!TIP]
    > <P>Despite its name, the <STRONG>Operation number</STRONG> field accepts any string value. Ensure the value is unique because when more than one Blank Operation contains the same <STRONG>Operation number</STRONG>, Retail POS executes only the first one it receives.</P>

    
    The **Blank Operation param** field enables you to send an optional string parameter. The **Operation number** and **Blank Operation param** values combine to form the method signature of your Blank Operation. In this scenario, set the **Operation number** to MyTask and leave the **Blank Operation param** value to My Param.

3.  You use the fields under the **Appearance** tab on the right side of the **Configure button** form to customize the look and feel of the button. For example, you can set the text value that displays on the button when Retail POS is launched. Change the button name to **MyOperation**, as shown in the following image:
    
    ![Deploying Blank Operation](images/JJ937970.DeployingBlankOperation(en-us,AX.60).png "Deploying Blank Operation")
    

    > [!WARNING]
    > <P>The preceding steps represent a temporary configuration of a Retail POS button. Any register updates received from Microsoft Dynamics AX for Retail Headquarters eliminate this configuration. To configure this button in Retail Headquarters, see <A href="setting-up-screen-layouts.md">Setting up screen layouts</A>.</P>



### Add your custom logic to the Blank Operation

1.  Open Retail POS Plug-ins from the folder where you installed the Retail POS SDK. For more information about how to install Retail POS Plug-ins, see [Install the Retail SDK](install-retail-sdk-retail-pos-plug-ins.md).
    

    > [!WARNING]
    > <P>When customizing Retail POS Plug-ins, we recommend that you back up your Retail SDK folder, so that you can revert to the original assemblies.</P>



2.  Open the Services folder and double-click the Services Visual Studio solution file.

3.  Go to the **Blank Operations** project and expand it.

4.  Open the BlankOperation.cs file and find the BlankOperation method, as shown in the following C\# code example:
    
    ``` 
    
            public void BlankOperation(IBlankOperationInfo operationInfo, IPosTransaction posTransaction)
    ```
    
    Notice the BlankOperation method takes two parameters: an operationInfo object and a posTransaction object. The operationInfo object contains the MyTask **Operation number** you set on the **MyOperation** button of the Retail POS register. Retail POS uses that **Operation number** to identify the Blank Operation that is being passed.
    
    The posTransaction object contains all the information about the current transaction. This includes line items, price, customer and payment information.
    
    Several Blank Operations can be passed to Retail POS simultaneously. Use a C\# Switch statement on the operationInfo.OperationId value to capture the specific one you need. You can do this by adding the following code to the **BlankOperation** method.
    
    ``` 
    
            public void BlankOperation(IBlankOperationInfo operationInfo, IPosTransaction posTransaction)
            {
                switch (operationInfo.OperationId)
                {
                    case "MyTask":
                    //TODO: insert method call to your custom logic
                    MessageBox.Show(“My new Blank Operation has executed.”);
                   break;
                }
    ```

5.  Compile the BlankOperations project.

6.  Copy your new assembly to the Pos\\Services\\Extension folder and launch Retail POS. Click the **Cashier Tasks** button and then click the **MyOperation** button. The following message box is displayed:
    
    ![BlankOperationMyTaskExecuted](images/JJ937970.BlankOperationMyTaskExecuted(en-us,AX.60).png "BlankOperationMyTaskExecuted")
    
    For a complete example of using a **Blank Operation** to customize Retail POS, see [Walkthrough: Adding an Image to Product Search Results](walkthrough-adding-an-image-to-product-search-results.md).

  



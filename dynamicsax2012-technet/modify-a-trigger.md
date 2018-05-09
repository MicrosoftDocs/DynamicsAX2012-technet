---
title: Modify a trigger
TOCTitle: Modify a trigger
ms:assetid: 07325aca-5ae7-4179-8850-108c1d78c0ff
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ937966(v=AX.60)
ms:contentKeyID: 50950755
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Modify a trigger 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

You use triggers to capture events that fire before and after Microsoft Dynamics AX for Retail POS operations. You can insert custom logic before the operation runs or after it has completed. The Retail POS IOperationTriggers interface introduces new generic triggers called the PreProcessOperation and PostProcessOperation. These triggers run at the beginning and end of all POS operations. For more information about triggers, see [Extend Point of Sale](extend-point-of-sale.md).

### How to modify the OperationsTrigger project

1.  Go to the folder where you installed the Retail POS SDK and open the Microsoft Dynamics AX for Retail POS Plug-ins folder. For information about how to install Retail POS Plug-ins, see [Install the Retail SDK](install-retail-sdk-retail-pos-plug-ins.md). Open the **Triggers** folder and double-click the **Triggers** Visual Studio solution file.

2.  Right-click the **OperationsTrigger** project name and click **Rename**. Change the assembly name to one of your choosing. When customizing Retail POS Plug-ins, we recommend that you give the modified assemblies new names. The original assemblies will then remain available if you need to revert back to them.
    

    > [!WARNING]
    > <P>For most customizations of Retail POS services or triggers, there can only be one instance of the implementation in the Retail POS runtime directory or Retail POS will not start. The exceptions to this are customizations of the Blank Operation or InteractionsDefault services.</P>

    
    You have to add references to the following assemblies located in the Retail POS runtime folder:
    
      - DevExpress.Utils.v11.2.dll
    
      - POSProcesses.dll
    
    You might also have to add a reference to the System.Windows.Forms.dll from the .NET Framework folder.

3.  You will update the **GiftCardBalance** operation by asking the customer if they want to add to their balance after it has been verified. Open the **OperationTriggers.cs** file and locate the PostProcessOperation method. Add the following C\# code:
    
        public void PostProcessOperation(IPosTransaction posTransaction, PosisOperations posisOperation)
                {            
                    if (posisOperation == PosisOperations.GiftCardBalance)
                    {
                        using (var form = new LSRetailPosis.POSProcesses.frmMessage("Would you like to add to your gift card amount?", MessageBoxButtons.OKCancel, MessageBoxIcon.Question))
                        {
                            LSRetailPosis.POSProcesses.POSFormsManager.ShowPOSForm(form);
                            if (form.DialogResult == DialogResult.OK)
                            {
                               //reference existing or new logic for adding money to customer gift cards
                            }
                        }
        
                    }
                    else
                    {
                        LSRetailPosis.ApplicationLog.Log("IOperationTriggersV1.PostProcessOperation", "After the operation has been processed this trigger is called.", LSRetailPosis.LogTraceLevel.Trace);
                    }
                }

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


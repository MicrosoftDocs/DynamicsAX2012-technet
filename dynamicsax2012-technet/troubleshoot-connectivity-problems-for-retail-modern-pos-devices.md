---
title: Troubleshoot connectivity problems for Retail Modern POS devices
TOCTitle: Troubleshoot connectivity problems for Retail Modern POS devices
ms:assetid: 79c4e750-85ba-4450-9143-87659aa387ae
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn876713(v=AX.60)
ms:contentKeyID: 63385373
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Troubleshoot connectivity problems for Retail Modern POS devices 


This topic explains how to troubleshoot and fix errors that occur when activating a modern point of sale (MPOS) device. To perform these tasks, a user must have access to Headquarters, must have IT Administrator rights on the computers that are running the Retail Server, Real-time Services, and the channel database, and must be assigned to a POS permission group that has device activation rights.

Permissions for a user can be modified after they have been assigned to a POS permission group in the **Worker** \> **Retail** \> **POS Permissions** form. For more information, see [Set up user accounts and the POS user group](set-up-user-accounts-and-the-pos-user-group.md).


> [!WARNING]
> <P>In Retail essentials, the forms that you use to complete some tasks might include only a subset of the controls that are available for other configurations of Retail. If a topic about these forms describes controls that you don't see, it may be because you’re using Retail essentials.</P>
> <P>MPOS cannot be used with Retail essentials.</P>



## Terminal not assigned to store

1.  Go to **Retail** \> **Setup** \> **POS** \> **POS registers**.

2.  Select the register that you are trying to activate the device for, and then on the **Register** tab, click **Edit**.

3.  Check the **Store number** value. If it is empty or contains the wrong store number, enter the correct value.

4.  Click **Close** to save your changes.

5.  Go to **Retail** \> **Periodic** \> **Data distribution** \> **Distribution schedule**.

6.  Run job **1090 (Registers)** and wait for it to finish.

7.  Activate the device again using the correct information.

8.  The device should now activate successfully.

## Worker not assigned to store

1.  Go to **Retail** \> **Common** \> **Workers**.

2.  Select the worker (Operator ID) that you are trying to activate the device for and then on the Worker tab, click **Edit**.

3.  Check the **Address Book** value under **Other information**. If it is empty or contains the wrong address book, enter the correct value.

4.  Click **Close** to save your changes.

5.  Go to **Retail** \> **Common** \> **Retail channels** \> **Retail stores**.

6.  Select the store that you are trying to activate the device for, and then on the Store tab, click **Edit**.

7.  Under **Address book** \> **Employee address book** verify that the address book is the one the worker belongs to. If it is the wrong address book, either change to the correct address book, or assign the employee to the correct address book.

8.  Click **Close** to save your changes.

9.  Go to **Retail** \> **Periodic** \> **Data distribution** \> **Distribution schedule**.

10. Run jobs **1060 (Staff)** and **1070 (Channel Configuration)** and wait for them to finish.

11. Activate the device again using the correct information.

12. The device should now activate successfully.

## Incorrect staff ID or password

1.  Go to **Retail** \> **Common** \> **Workers**.

2.  Select the worker (Operator ID) that you are trying to activate the device for and then on the Worker tab, click **Edit**.

3.  In the left pane, click **Profile**, and then check the personnel number. This should be same as the Operator ID you are trying to use for activation.

4.  In the left pane, click **Retail**, and then change the password.

5.  Go to **Retail** \> **Periodic** \> **Data distribution** \> **Distribution schedule**.

6.  Run job **1060 (Staff)** and wait for it to finish.

7.  Activate the device again using the correct operator ID and updated password.

8.  The device should now activate successfully.

## Device already activated

1.  Click **Retail** \> **Setup** \> **Devices**.

2.  Select the number of the device that you are trying to activate.

3.  In the **Activation status** column, check whether the status is **activated** or **deactivated**.

4.  Change the **Activation status** to **Pending**.

5.  Activate the device again.

6.  The device should now activate successfully.

## Channel database connection failed

To perform the following procedure, you must be an administrator on the Retail server computer and the Channel database computer.

In the headquarters environment, perform the following steps:

1.  Go to **Retail** \> **Setup** \> **Retail scheduler** \> **Channel integration** \> **Channel database**.

2.  Select the channel database ID that you are trying to connect to.

3.  On the Retail channel FastTab, validate that the server name and database name are accurate.

Log in to the computer that hosts the Retail server.

1.  Check whether the Retail server is configured to match the correct channel database.

2.  Check whether the channel database ID matches the connection string of the database that you are accessing for the store where the Modern POS will be used.

If you had to modify the channel database connection string (channel database ID), you must run the Channel configuration job and reset IIS.

1.  In the channel database form (**Retail** \> **Setup** \> **Retail Scheduler** \> **Channel integration** \> **Channel database**), run the Channel Configuration job (1070).

2.  On the Retail server, perform an App Pool Refresh or iisreset.

3.  Activate the device again using the correct information.

4.  The device should now activate successfully.

## Real-time Service connection failed

You must be a local administrator on the computers that host the Real-time Service and the Retail Server to perform these steps.

1.  Go to **Retail** \> **Setup** \> **Parameters** \> **Retail shared parameters**.

2.  In the left pane, select **General**.

3.  Under the **Devices** section, make sure that **Real-time Service profile for device activation** is selected for the correct Real-time Service profile.

4.  Go to **Retail** \> **Setup** \> **Retail scheduler** \> **Channel integration** \> **Real-time Service profiles**.

5.  Check whether the server name is correct, and whether the common name is the subject name of your certificate.

Log in to the computer that hosts the Real-time Service.

1.  Open IIS and check whether the Real-time Service is running.

2.  Refresh the App pool or perform an iisreset.

Log in to the computer that hosts the Retail Server.

1.  If you had to change the Real-time Service URL, refresh the app pool or perform an iisreset for the Retail Server.

2.  Activate the device again using the correct information.

3.  The device should now activate successfully.

## Server not responding

You must be a local administrator on the computers that host the AOS, Real-time Service, and Retail Server to perform this procedure.

1.  Validate that the AOS windows service, Real-time Service (Web service), and Retail Server (Web service) are running.

2.  Log in to the computer that hosts the Retail Server.

3.  Check that the Retail Server is configured to use the correct URL and port. This should be the same URL that you use to activate from the Modern POS device.

4.  Refresh the app pool or perform an iisreset for the Retail Server.

5.  Activate the device again using the correct information.

6.  The device should now activate successfully.

## See also

[IISADMIN Service](http://technet.microsoft.com/en-us/library/cc735102.aspx)

[Start or Stop an Application Pool](http://technet.microsoft.com/en-us/library/cc732742.aspx)

  



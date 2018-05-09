---
title: Customize the Data in a Commerce Entity
TOCTitle: Customize the Data in a Commerce Entity
ms:assetid: 3857369f-d293-4897-90b7-bd8aefcbb3a7
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ916616(v=AX.60)
ms:contentKeyID: 50934006
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Customize the Data in a Commerce Entity 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The [CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md) class is the base class of all entities in the commerce runtime (CRT). The CommerceEntity class is a property bag of key value pairs of C\# properties. These properties provide string representations of fields from the database so that you do not need to remember the names of columns in your database when you write code. When you use commerce runtime APIs, you must use commerce entities because the base class expects all the parameters to be of type CommerceEntity. But after you retrieve data from the database and return it from the data manager, you can create regular C\# objects that you can use in workflow or services.

For any existing data type, if you add one or more new fields to a table in Microsoft Dynamics AX, the commerce entity automatically includes those fields as long as you make changes to the stored procedure or view to return the additional field. For example, you might want to verify the age of a customer for a particular transaction, but that information is not included in the customer object. To enable the customer commerce entity to include the customer age automatically, you can add a field in a Microsoft Dynamics AX table to store the customer age and update the view in the commerce runtime to also return customer age.


> [!NOTE]
> <P>Adding customer age is an example to demonstrate this concept. You could also access customer age through other means.</P>



## Updating Properties in a Commerce Entity

To update the properties that are available in the commerce entity, you must do the following:

  - Identify the field in Microsoft Dynamics AX that you want to expose in the commerce entity. If the data you want does not exist in an existing table, you must create a new field on a new or existing table.

  - Modify the stored procedure or view that specifies the data that is passed from Microsoft Dynamics AX to the commerce entity.

  - Update the commerce entity to include the new field.

### Create a field in Microsoft Dynamics AX

1.  Create the field you want to use to pass data from Microsoft Dynamics AX to the commerce entity. Expand the appropriate table node for the new field, right-click **Fields**, point to **New**, and then click the data type you want for the field.
    

    > [!NOTE]
    > <P>If the field you want to use already exists, go directly to the next section to modify the view that corresponds to the commerce entity you want to update.</P>



2.  Specify properties for your new field. For more information, see [Tables Overview](https://technet.microsoft.com/en-us/library/bb314725\(v=ax.60\)).

3.  Add the new field in the CRT database.

4.  Update the Synch service to pass the new field.

### Modify the view to include the new field

1.  Connect to your database server in SQL Server Management Studio.

2.  Expand the **Databases** node, expand the node for your CRT database, expand the Views node, and then find the view that corresponds to the data entity you want to modify.

3.  Right-click the view, point to **Script View as**, point to **ALTER To**, and then click **New Query Editor Window**.

4.  Update the view to include the field you created.

### Update the commerce entity

1.  Open the commerce entity in Visual Studio.

2.  Add a String variable to represent the property you are adding.
    
    For example,
    
        private const string CustAge = “AGE”;

3.  Add a method to cast the value from the field in Microsoft Dynamics AX as a string and set it as the value for the property.
    
    For example,
    
        public string Age
        {
            get { return (string)this[CustAge]; }
            set { this[CustAge] = value; }
        }

## See also

[Online Store](online-store.md)

[Retail Modern Point of Sale](retail-modern-point-of-sale.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


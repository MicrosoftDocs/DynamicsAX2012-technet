---
title: 'Walkthrough: Exposing an X++ Class as a Data Contract'
TOCTitle: 'Walkthrough: Exposing an X++ Class as a Data Contract'
ms:assetid: 239bbd12-076c-4fe0-9f67-cd5feef90c71
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg844225(v=AX.60)
ms:contentKeyID: 35241594
ms.date: 04/17/2013
mtps_version: v=AX.60
---

# Walkthrough: Exposing an X++ Class as a Data Contract 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft Dynamics AX supports the use of .NET and X++ types as data contracts for service operation input and return parameters. This enables you to pass complex data types without having to explicitly implement XML serialization and deserialization. In this walkthrough, you will create a data contract class in X++ and use it as a return value and parameter in a service. You will create a service group and deploy the service on a basic inbound integration port.

The X++ data contract attributes are resemble the data contract attributes for .NET types. For more information about data contracts in the .NET Framework, see [Using Data Contracts](http://go.microsoft.com/fwlink/?linkid=139795).

This walkthrough illustrates the following tasks:

  - Creating the data contract class.

  - Creating the service contract and the service.

  - Deploying the service by creating a service group and a basic inbound integration port.

  - Verifying that the service is deployed correctly by activating the port and viewing the Web Services Description Language (WSDL) file.

## Prerequisites

To complete this walkthrough you will need:

  - Microsoft Dynamics AX 2012

  - A license file that has access to the Development workspace

## Create the Data Contract

To create the data contract, you must first create an X++ class. You will apply the attributes to specify that the class is a data contract and that it must be serialized. First, you create the data contract class that will contain the employee information.

### To create the data contract

1.  In the AOT, right-click the **Classes** node, and then click **New Class**. The new class displays under the **Classes** node.

2.  Expand the new class, right-click on the **classDeclaration** method, and then click **View Code** to open the **Editor** window.
    
    Replace the code in the **Editor** window with the following code and save your changes. This code renames the class to EmployeeTest, adds the DataContractAttribute attribute to the class, and defines some data members. These members are not automatically exposed as part of the data contract. You must create methods and use the DataMember attribute as illustrated in subsequent steps.
    ```X++
        [DataContractAttribute]
        public class EmployeeTest
        {
            str employeeName;
            int employeeAge;
            utcdatetime employeeBirthDate;
            
        }
    ```
3.  Right-click the **EmployeeTest** class and then click **Properties**.

4.  Set the **RunOn** property to **Called From**.

5.  Right-click the **EmployeeTest** class, click **New**, and then click **Method**.
    
    Replace the code in the **Editor** window with the following code and save your changes. This creates a class member called name and applies the DataMemberAttribute attribute to it.
    ```X++
        [DataMemberAttribute]
        public str name(str _employeeName = employeeName)
        {
            employeeName = _employeeName;
            return employeeName;
        }
    ```
6.  Right-click the **EmployeeTest** class, click **New**, and then click **Method**.
    
    Replace the code in the **Editor** window with the following code and save your changes. This creates a class member called age and applies the DataMemberAttribute attribute to it.
    ```X++
        [DataMemberAttribute]
        public int age(int _employeeAge = employeeAge)
        {
            employeeAge = _employeeAge;
            return employeeAge;
        }
    ```
7.  Right-click the **EmployeeTest** class, click **New**, and then click **Method**.
    
    Replace the code in the **Editor** window with the following code and save your changes. This creates a class member called birthDate and applies the DataMemberAttribute attribute to it.
    ```X++
        [DataMemberAttribute]
        public utcdatetime birthDate(utcdatetime _employeeBirthDate = employeeBirthDate)
        {
            employeeBirthDate = _employeeBirthDate;
            return employeeBirthDate;
        }
    ```
## Create the Service Contract

After you have created a data contract, you must now create the service contract in the AOT. The service contract is implemented by the class that is exposed as a service by using the data contract you just created. It is also referred to as the service class. The methods in this class become the service operations.

To make the service available after you create the service contract, you must deploy it as a service. To deploy a service you must create an integration port. In the simplest case, you create a basic inbound port when you auto-deploy the service from the AOT. For more information about how to create integration ports, see [Integration ports](integration-ports.md) and [Managing integration ports](managing-integration-ports.md).

### To create the service contract class

1.  Right-click the **Classes** node and then click **New Class**.

2.  Right-click the new class, click **Rename**, and then enter **EmployeeServiceContractTestClass**.

3.  Right-click **EmployeeServiceContractTestClass** and then click **Properties** to display the **Properties** window.

4.  Set the **RunOn** property to **Server**.

5.  Right-click the **EmployeeServiceContractTestClass**, click **New**, and then click **Method**.
    
    Replace the code in the **Editor** window with the following code. This creates a class method called getEmployee which returns the data contract class EmployeeTest.
    ```X++
        [SysEntryPointAttribute(true)]
        public EmployeeTest getEmployee()
        {
            EmployeeTest employee;
            EmployeeTest manager;
            utcdatetime dt = 1969-02-03T00:00:00;
            ;
            employee = new EmployeeTest();
            employee.age(40);
            employee.name('Molly Clark');
            employee.birthDate(dt);
        
        
        
            return employee;
        }
    ```
### To create the service contract

1.  Open the AOT and expand the **Services** node.

2.  In the AOT, right-click the **Services** node, and then click **New Service**.

3.  Right-click the new service and then click **Properties** to display the **Properties** window.

4.  Set the **Name** property to **EmployeeServiceTest**.

5.  Set the **Class** property to **EmployeeServiceContractTestClass**. This is the service contract class you just created.

6.  Expand the **EmployeeServiceTest** node, right-click the **Operations** node, and then click **Add Operation**.

7.  In the **Add service operations** form, select the **Add** field for the getEmployee service operation.
    
    Click **OK** and save your changes.

## Deploy the Data Contract Service By Using a Basic Inbound Integration Port

After you create the service contract, you must deploy it as a service. To deploy a service you must create an integration port. In the simplest case, you create a basic inbound port when you deploy the service in a service group from the AOT.

### To create a service group and deploy the service on a basic port

1.  In the AOT, right-click the **Service Groups** node, and then select **New Service Group**.

2.  Right-click the new service group, click **Rename** and enter **EmployeeTestServiceGroup**.

3.  Right-click **EmployeeTestServiceGroup** and then click **Open New Window** to open a new window.

4.  Drag and drop the **EmployeeServiceTest** from the **Services** node onto the **EmployeeTestServiceGroup**. Right-click the service group and then click **Save**.

5.  Right-click **EmployeeTestServiceGroup** and then click **Deploy Service Group**.
    
    To start this service every time that the AOS is restarted, set the **AutoDeploy** property for the service group to **Yes**.
    

    > [!NOTE]
    > <P>This step may take some time. When the process is complete, you will see messages indicating success or error conditions in the <STRONG>Infolog</STRONG>.</P>

    

    > [!WARNING]
    > <P>Do not deploy a custom service and a document service to the same port. The resulting service references will not compile.</P>



## Verify deployment of the service

The previous steps created a basic integration port. You must activate the port to make the service available to external clients.

### To verify deployment of the service

1.  Open the **Inbound ports** form. In the Microsoft Dynamics AX client, click **System Administration** \> **Setup** \> **Services and Application Integration Framework** \> **Inbound ports**.

2.  If the **EmployeeTestServiceGroup** has a green check mark next to it, the port is active. If it does not, select **EmployeeTestServiceGroup** and then click **Activate** to activate the basic port.

3.  Use your browser to view the WSDL file at the address specified in **WSDL URI** field of the **Inbound ports** window. Presence of a WSDL file indicates the service is deployed and may be called by an external client.

## See also

[Using Data Contracts in X++](using-data-contracts-in-x.md)

[Consuming Microsoft Dynamics AX Services from an External Client](consuming-microsoft-dynamics-ax-services-from-an-external-client.md)

[Walkthrough: Exchanging documents by using the NetTcp adapter](walkthrough-exchanging-documents-by-using-the-nettcp-adapter.md)


---
title: 'Walkthrough: Adding customer preferences to the Retail online sample store'
TOCTitle: 'Walkthrough: Extending the Retail online sample store'
ms:assetid: 5771233d-d844-41f9-9f09-9d17e57bffa2
ms:mtpsurl: https://technet.microsoft.com/library/Dn720786(v=AX.60)
ms:contentKeyID: 62231587
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Walkthrough: Adding customer preferences to the Retail online sample store 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

To make the new customer preference data available in SharePoint pages, you must modify code in Retail SDK\\Online Channel\\Storefront\\Storefront.sln. First, you add code to make the new fields available in the data model and the view model. Then you modify the web controls, and then you modify the store pages to enable display, entry, and modification of the new fields. Finally, you rebuild and redeploy the solution.

You make the new field available on the Customer control, which is included on the Account page and the Edit Profile. On the Account page, the field is read-only. Customers can edit the field on the EditProfile page.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><img src="images/Dn768211.TopicIcons_Walkthrough(AX.60).png" title="Walkthrough" alt="Walkthrough" />
<p>Prerequisites</p>
<p>Make the new fields available in the data model and the view model</p>
<p>Make changes to the controller</p>
<p>Make the new fields visible on the site pages</p>
<p>Add code to ControlResources.Designer.cs</p>
<p>Add text to ControlResources.resx</p></td>
<td><img src="images/Dn507140.TopicIcons_Resources(AX.60).png" title="Resources" alt="Resources" />
<p><a href="online-store.md">Online Store</a></p></td>
</tr>
</tbody>
</table>


## Prerequisites

These walkthroughs illustrate adding a field to a retail channel that enables customers to opt in to receive special offers by email. In this scenario, the retailer wants to indicate whether customers wish to receive email about special offers, either in an online store or in a modern POS client. The walkthroughs should be completed in the following order:

1.  [Walkthrough: Adding a table for customer preferences to the AX 2012 database](walkthrough-adding-a-table-for-customer-preferences-to-the-ax-2012-database.md)

2.  [Walkthrough: Extending the CRT to add customer preference data for Retail clients](walkthrough-extending-the-crt-to-add-customer-preference-data-for-retail-clients.md)

3.  [Walkthrough: Extending retail data distribution infrastructure for customer preferences](walkthrough-extending-retail-data-distribution-infrastructure-for-customer-preferences.md)

4.  [Walkthrough: Adding customer preferences to the Retail online sample store](walkthrough-adding-customer-preferences-to-the-retail-online-sample-store.md) (online store only)

## Make the new fields available in the data model and the view model

In the SharePoint.Web.Services project of the Storefront.sln solution, you modify ViewModel\\Customer.cs and ObjectModel\\Customermapper.cs. You modify the Javascript files Customer.js and CustomerDisplay.js inStorefront\\Scripts\\Scripts\\ViewModel.

### To modify the view model

1.  Open the Retail SDK\\Online channel folder and open Storefront.sln. and navigate to Modify Customer.cs in SharePoint.Web.Services\\ViewModel\\Customer.cs by adding the following code at the end of the file:

2.  Open Customer.cs in SharePoint.Web.Services\\ViewModel.

3.  Add the following code at the end of the file:
    
    ``` 
           [DataMember]
            public Enum EmailOptIn { get; set; }
    ```

### To map the new field to the object model

1.  You modify SharePoint.Web.Services/ObjectModel/ CustomerMapper.cs to create a mapping between the new fields in the data model and the view model.

2.  You add the new fields to ConvertToViewModel and ConvertToDataModel methods.
    
    Add the following lines of code to the ConvertToViewModel method after the first If statement.
    
        bool emailOptIn = false; /// NEW Code
                    var emailOptInExtensionProperty = customer.ExtensionProperties.Where(c => c.Key == "EMAILOPTIN").FirstOrDefault();
                    if (emailOptInExtensionProperty != null)
                    {
                        int intEmailOptIn = (int)emailOptInExtensionProperty.Value.GetPropertyValue(); // NEW Code
                        emailOptIn = intEmailOptIn == 0 ? false : true;
                    }

3.  Add the following code after the statement LoyaltyCardNumber – customer.LoyaltyCardNumber,.
    
        EmailOptIn = emailOptIn // NEW Code
    
    The following example shows the ConvertToViewModel method after adding the code.
    
        internal static ViewModel.Customer ConvertToViewModel(DataModel.Customer customer)
                {
                    if (customer == null)
                    {
                        throw new ArgumentNullException("customer");
                    }
                    bool emailOptIn = false; /// NEW Code
                    var emailOptInExtensionProperty = customer.ExtensionProperties.Where(c => c.Key == "EMAILOPTIN").FirstOrDefault();
                    if (emailOptInExtensionProperty != null)
                    {
                        int intEmailOptIn = (int)emailOptInExtensionProperty.Value.GetPropertyValue(); // NEW Code
                        emailOptIn = intEmailOptIn == 0 ? false : true;
                    }
        
                    ViewModel.Customer vmCustomer = new ViewModel.Customer()
                    {
                        AccountNumber = customer.AccountNumber,
                        Addresses = ConvertToViewModel(customer, customer.Addresses),
                        Email = customer.Email,
                        FirstName = customer.FirstName,
                        LastName = customer.LastName,
                        MiddleName = customer.MiddleName,
                        Phone = customer.Phone,
                        PhoneExt = customer.PhoneExt,
                        RecordId = customer.RecordId,
                        Url = customer.Url,
                        PrimaryAddress = AddressMapper.ConvertToViewModel(customer.GetPrimaryAddress(), customer),
                        LoyaltyCardNumber = customer.LoyaltyCardNumber,
                        EmailOptIn = emailOptIn // NEW Code
                    };
        
                    return vmCustomer;
                }

4.  Add the following line of code to the UpdateDataModel method.
    
        dataModelCustomer["EMAILOPTIN"] = Convert.ToInt64(customer.EmailOptIn); ///NEW Code
    
    The following example shows where the line is added.
    
    ``` 
    internal static DataModel.Customer UpdateDataModel(DataModel.Customer dataModelCustomer, ViewModel.Customer customer)
            {
                if (customer == null)
                {
                    throw new ArgumentNullException("customer");
                }
    
                if (dataModelCustomer == null)
                {
                    throw new ArgumentNullException("dataModelCustomer");
                }
    
                dataModelCustomer.Email = customer.Email;
                dataModelCustomer.FirstName = customer.FirstName;
                dataModelCustomer.LastName = customer.LastName;
                dataModelCustomer.MiddleName = customer.MiddleName;
                dataModelCustomer.Phone = customer.Phone;
                dataModelCustomer.PhoneExt = customer.PhoneExt;
                dataModelCustomer.Url = customer.Url;
                dataModelCustomer.Language = "en-us"; // only support en-Us in the UI at this time 
                dataModelCustomer. ["EMAILOPTIN"] = Convert.ToInt64(customer.EmailOptIn); ///NEW Code
    
    
    ```

5.  Add the following example code to ConvertToDataModel immediately before the return statement:
    
    ``` 
                dmCustomer["Age"] = customer.Age;
                dmCustomer["SpecialOffers"] = customer.SpecialOffers;
    ```

### To modify Customer.js

1.  Open Customer.js in the Scripts\\Scripts folder of Storefront.sln.

2.  Add the following code to the function updateCustomer.
    
        /// NEW Code
                    if ($view.find('.msax-EmailOptInCheckBox').is(':checked')) {
                        customer.EmailOptIn = true;
                    }
                    else {
                        customer.EmailOptIn = false;
                    }//NEW code
    
    The following example shows the function after the code is added.
    
    ``` 
       // Update a customer
        this.UpdateCustomer = function () {
            if (!Microsoft.Trigger($view, "UpdateCustomer")) {
                return;
            }
    
            validator.Validate($view);
            // NEW Code
            if ($view.find('.msax-EmailOptInCheckBox').is(':checked')) {
                customer.EmailOptIn = true;
            }
            else {
                customer.EmailOptIn = false;
            } //NEW code
    
            if (validator.IsValid) {
                services.UpdateCustomer(customer);
            }
        }
    ```

### To modify CustomerDisplay.js

1.  Open CustomerDisplay.js in the Scripts\\Scripts folder of Storefront.sln.

2.  Add the following code to the Initialize function.
    
        // NEW Code
                if (customer.EmailOptIn) {
                    $view.find('.msax-EmailOptInCheckBox').prop('checked', true);
                }
                else {
                    $view.find('.msax-EmailOptInCheckBox').prop('checked', false);
                }
        
                $view.find('.msax-EmailOptInCheckBox').attr("disabled", true);//NEW code
    
    The following example shows the Initialize function after adding the code.
    
        // CustomerViewModel constructor.
            function Initialize() {
                // Attach the Render event to the AfterRefresh
                // event so when the data is loaded it will be
                // displayed immediately.
                services.OnGetCustomerSuccess(onGetCustomerSuccess);
                services.OnGetCustomerFailure(onGetCustomerFailure);
                
                binder = new Microsoft.Dynamics.Retail.SharePoint.Web.UI.TemplateBinder(
                    $view.find('.msax-CustomerDisplayTemplate'),
                    $view.find('.msax-CustomerDisplayContainer'));
        
                // Set the customer control to refresh upon page load,
                me.GetCustomer();
            }
        
            // bind the customer to the display only fields
            this.BindCustomerDisplayData = function (customer) {
                $view.find('.msax-CustomerDisplayAddress1').text(customer.FirstName + ' ' + customer.MiddleName + ' ' + customer.LastName);
                $view.find('.msax-CustomerDisplayAddress2').text(customer.PrimaryAddress.StreetNumber + ' ' + customer.PrimaryAddress.Street);
                $view.find('.msax-CustomerDisplayAddress3').text(customer.PrimaryAddress.City + ' ' + customer.PrimaryAddress.State + ' ' + customer.PrimaryAddress.ZipCode);
                $view.find('.msax-CustomerDisplayAddress4').text(customer.PrimaryAddress.Country);
                $view.find('.msax-CustomerDisplayPrimaryEmail').text(customer.Email);
                $view.find('.msax-CustomerDisplayLoyaltyNumber').text(customer.LoyaltyCardNumber);
                // NEW Code
                if (customer.EmailOptIn) {
                    $view.find('.msax-EmailOptInCheckBox').prop('checked', true);
                }
                else {
                    $view.find('.msax-EmailOptInCheckBox').prop('checked', false);
                }
        
                $view.find('.msax-EmailOptInCheckBox').attr("disabled", true); //NEW code
        
            }

## Make changes to the controller

### To modify SharePointWebControls/Customer/Customer.cs

1.  Open Customer.cs in the SharePoint.Web.Controls/Customer folder.

2.  Add the following code to the RetailWebControl class.
    
        private HtmlInputCheckBox emailOptIn; // NEW code
    
    The following example shows the after adding the code to the RetailWebControl class.
    
        public class Customer : RetailWebControl
            {
                private HtmlInputText firstName;
                private HtmlInputText lastName;
                private HtmlInputText email;
                private HtmlInputText phone;
        
                private HtmlInputText street;
                private HtmlInputText city;
                private HtmlInputText state;
                private HtmlInputText zipCode;
                private HtmlInputText country;
                private HtmlInputCheckBox emailOptIn; // NEW code

3.  Add the following two code blocks to the GetCustomerTemplate method.
    
      - This code creates the checkbox.
        
            ///NEW code
                        this.emailOptIn = ControlFactory.CreateCheckBox("msax-EmailOptInCheckBox");
                        this.emailOptIn.AddAttribute(AXDataBindAttributes.Value, "EmailOptIn");
                        HtmlLabel emailOptInLabel = ControlFactory.CreateLabel(ControlResources.CustomerEmailOptIn, null, this.emailOptIn);
                        HtmlFieldPanel emailOptInContainer = ControlFactory.CreateFieldPanel(emailOptInLabel, this.emailOptIn, "msax-CustomerEmailOptIn"); //NEW code
    
      - This code adds the control to the container.
        
            contactInfo.Controls.Add(emailOptInContainer);

4.  The following example shows the GetCustomerTemplate method with the new code added.
    
        private HtmlTemplate GetCustomerTemplate()
                {
                    // Create the master template to put the shopping cart table in.
                    HtmlTemplate template = new HtmlTemplate();
                    template.AddCssClass("msax-CustomerTemplate");
        
                    this.CssClass = "msax-CustomerControl";
        
                    
                    HtmlFieldSet contactInfo = ControlFactory.CreateFieldSet("msax-ContactInfoControls");
                    HtmlParagraph contactInfoParagraph = ControlFactory.CreateParagraph("msax-ContactInfoHeader");
                    contactInfoParagraph.InnerText = ControlResources.CustomerContactInformation;
        
                    // Create the controls     
                    this.email = ControlFactory.CreateTextBox("msax-EmailTextBox");
                    this.email.AddAttribute(AXDataBindAttributes.Value, "Email");
                    this.email.AddRegularExpressionValidator(ControlResources.CustomerEmailNotSpecified, @"\w+([-+.]\w+)*@\w+([-.]\w+)*\.\w+([-.]\w+)*");
                    this.email.MaxLength = 255;
                    HtmlLabel emailLabel = ControlFactory.CreateLabel(ControlResources.CustomerEmail, null, this.email);
                    HtmlFieldPanel emailContainer = ControlFactory.CreateFieldPanel(emailLabel, this.email, "msax-CustomerEmail");
                    
                    this.firstName = ControlFactory.CreateTextBox("msax-FirstNameTextBox");
                    this.firstName.AddAttribute(AXDataBindAttributes.Value, "FirstName");
                    this.firstName.AddRequiredFieldValidator(ControlResources.CustomerFirstnameNotSpecified, "");
                    this.firstName.MaxLength = 100;
                    HtmlLabel firstNameLabel = ControlFactory.CreateLabel(ControlResources.CustomerFirstName, null, this.firstName);
                    HtmlFieldPanel firstNameContainer = ControlFactory.CreateFieldPanel(firstNameLabel, this.firstName, "msax-CustomerFirstName");
        
                    this.lastName = ControlFactory.CreateTextBox("msax-LastNameTextBox");
                    this.lastName.AddAttribute(AXDataBindAttributes.Value, "LastName");
                    this.lastName.AddRequiredFieldValidator(ControlResources.CustomerLastnameNotSpecified, "");
                    this.lastName.MaxLength = 100;
                    HtmlLabel lastNameLabel = ControlFactory.CreateLabel(ControlResources.CustomerLastName, null, this.lastName);
                    HtmlFieldPanel lastNameContainer = ControlFactory.CreateFieldPanel(lastNameLabel, this.lastName, "msax-CustomerLastName");
        
                    this.phone = ControlFactory.CreateTextBox("msax-PhoneTextBox");
                    this.phone.AddAttribute(AXDataBindAttributes.Value, "Phone");
                    this.phone.MaxLength = 255;
                    HtmlLabel phoneLabel = ControlFactory.CreateLabel(ControlResources.CustomerPhone, null, this.phone);
                    HtmlFieldPanel phoneContainer = ControlFactory.CreateFieldPanel(phoneLabel, this.phone, "msax-CustomerPhone");
        
                    /// NEW code
                    this.emailOptIn = ControlFactory.CreateCheckBox("msax-EmailOptInCheckBox");
                    this.emailOptIn.AddAttribute(AXDataBindAttributes.Value, "EmailOptIn");
                    HtmlLabel emailOptInLabel = ControlFactory.CreateLabel(ControlResources.CustomerEmailOptIn, null, this.emailOptIn);
                    HtmlFieldPanel emailOptInContainer = ControlFactory.CreateFieldPanel(emailOptInLabel, this.emailOptIn, "msax-CustomerEmailOptIn");
                    /// NEW code
        
                    // Add the individual controls to the fieldset       
                    contactInfo.Controls.Add(contactInfoParagraph);
                    contactInfo.Controls.Add(emailContainer);
                    contactInfo.Controls.Add(firstNameContainer);
                    contactInfo.Controls.Add(lastNameContainer);
                    contactInfo.Controls.Add(phoneContainer);
        
                    contactInfo.Controls.Add(emailOptInContainer); //NEW code
        
                    HtmlFieldSet primaryAddressInfo = ControlFactory.CreateFieldSet("msax-AddressInfoControls");
                    HtmlParagraph primaryAddressInfoParagraph = ControlFactory.CreateParagraph("msax-AddressInfoHeader");
                    primaryAddressInfoParagraph.InnerText = ControlResources.CustomerAddressInformation;

### To modify SharePointWebControls/Customer/CustomerDisplay.cs

1.  Open CustomerDisplay.cs

2.  Add the following code line to the header.
    
        using System.Web.UI.HtmlControls; /// NEW Code

3.  Add the following code to the GetCustomerTemplate method.
    
        /// NEW code
                    HtmlLabel displayEmailOptInLabel = ControlFactory.CreateLabel(ControlResources.CustomerEmailOptIn, "msax-CustomerDisplayEmailOptInLabel");
                    HtmlInputCheckBox displayEmailOptIn = ControlFactory.CreateCheckBox("msax-CustomerDisplayEmailOptIn");
                    /// NEW code

4.  Add the following code to the GetCustomerTemplate method.
    
        /// NEW Code
                    displayFieldSet.Controls.Add(displayEmailOptInLabel);
                    displayFieldSet.Controls.Add(displayEmailOptIn);
                    /// NEW Code

5.  The following example shows the new code added to the GetCustomerTemplate method.
    
        private HtmlTemplate GetCustomerTemplate()
                {
                    // Create the master template to put the shopping cart table in.
                    HtmlTemplate template = new HtmlTemplate();
                    template.AddCssClass("msax-CustomerDisplayTemplate");
        
                    this.CssClass = "msax-CustomerDisplayControl";
        
                    HtmlFieldSet displayFieldSet = ControlFactory.CreateFieldSet("msax-CustomerDisplayControls");
        
                    HtmlLabel displayAddressLabel = ControlFactory.CreateLabel(ControlResources.CustomerDisplayAddressLabel, "msax-CustomerDisplayAddressLabel");
                    HtmlSpan displayAddressLine1 = ControlFactory.CreateSpan(string.Empty, "msax-CustomerDisplayAddress1");
                    HtmlSpan displayAddressLine2 = ControlFactory.CreateSpan(string.Empty, "msax-CustomerDisplayAddress2");
                    HtmlSpan displayAddressLine3 = ControlFactory.CreateSpan(string.Empty, "msax-CustomerDisplayAddress3");
                    HtmlSpan displayAddressLine4 = ControlFactory.CreateSpan(string.Empty, "msax-CustomerDisplayAddress4");
                    HtmlSpan displayAddressLine5 = ControlFactory.CreateSpan(string.Empty, "msax-CustomerDisplayAddress5");
                    
                    HtmlLabel displayEmailLabel = ControlFactory.CreateLabel(ControlResources.CustomerDisplayPrimaryEmail, "msax-CustomerDisplayPrimaryEmailLabel");
                    HtmlSpan displayEmail = ControlFactory.CreateSpan(string.Empty, "msax-CustomerDisplayPrimaryEmail");
        
                    /// NEW code
                    HtmlLabel displayEmailOptInLabel = ControlFactory.CreateLabel(ControlResources.CustomerEmailOptIn, "msax-CustomerDisplayEmailOptInLabel");
                    HtmlInputCheckBox displayEmailOptIn = ControlFactory.CreateCheckBox("msax-CustomerDisplayEmailOptIn");
                    /// NEW code
        
                    displayFieldSet.Controls.Add(displayAddressLabel);
                    displayFieldSet.Controls.Add(displayAddressLine1);
                    displayFieldSet.Controls.Add(displayAddressLine2);
                    displayFieldSet.Controls.Add(displayAddressLine3);
                    displayFieldSet.Controls.Add(displayAddressLine4);
                    displayFieldSet.Controls.Add(displayAddressLine5);
        
                    /// NEW Code
                    displayFieldSet.Controls.Add(displayEmailOptInLabel);
                    displayFieldSet.Controls.Add(displayEmailOptIn);
                    /// NEW Code
        
                    displayFieldSet.Controls.Add(displayEmailLabel);
                    displayFieldSet.Controls.Add(displayEmail);
        
                    template.Controls.Add(displayFieldSet);
                                
                    return template;
                }
            }

## Make the new fields visible on the site pages

Modify the following files in SharePoint.Web.Storefront/Controls project:

  - ControlResources.Designer.cs

  - ControlResources.resx

## Add code to ControlResources.Designer.cs

``` 
      /// <summary> NEW code
        ///   Looks up a localized string similar to Email for special offers:.
        /// </summary>
        internal static string CustomerEmailOptIn
        {
            get
            {
                return ResourceManager.GetString("CustomerEmailOptIn", resourceCulture);
            }
        }
        /// NEW code
```

The following example shows where the new code is added in ControlResourcesDisigner.cs.

``` 
  
        /// <summary>
        ///   Looks up a localized string similar to Share my information with Contoso partners..
        /// </summary>
        internal static string CustomerShareInformation {
            get {
                return ResourceManager.GetString("CustomerShareInformation", resourceCulture);
            }
        }

        /// <summary> NEW code
        ///   Looks up a localized string similar to Email for special offers:.
        /// </summary>
        internal static string CustomerEmailOptIn
        {
            get
            {
                return ResourceManager.GetString("CustomerEmailOptIn", resourceCulture);
            }
        }
        /// NEW code

        /// <summary>
        ///   Looks up a localized string similar to State:.
        /// </summary>
        internal static string CustomerState {
            get {
                return ResourceManager.GetString("CustomerState", resourceCulture);
            }
        }
        
```

## Add text to ControlResources.resx

Add text for the labels and messages to Storefront/Controls/ControlResources.resx as shown in the following table:

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Name</p></th>
<th><p>Value</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>CustomerEmailOptIn</p></td>
<td><p>Email for special offers</p></td>
<td><p>Checkbox for EmailOptIn</p></td>
</tr>
</tbody>
</table>

  



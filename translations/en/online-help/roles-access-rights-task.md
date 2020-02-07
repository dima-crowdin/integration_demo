
# Roles and access rights

In this section the Insights **Administrator** can find information about the initial setting of user types and roles in Visma.net Admin. It contains also steps for customizing access rights on roles and users done in Visma.net Insights.

<details>
<summary>Users</summary>

It is the Insights **Administrator** who has access to manage the access rights. The Insights **Administrator** is the user that has the **Administrator** role for the Insights application.

The (Insights) **Administrator** role is NOT the same as the **Super user** role.

*   The Insights **Administrator** has access to the administrative sections of the application:

	*   **Import** (of data)
	*   **Mapping** (of accounts)
	*   **Settings** (of access rights)

*   The **Super user** and all the other roles except **Administrator** have access only to the **Dashboards** section (the application content)

Another important distinction has to be made between a **role** and a **user type**: 

*   A **role** gives the user access to the application’s content (dashboards with elements).
*   A **user type** determines what functionality (adding **elements**, restoring an element to the original) a user has access to, inside the application.

So to have access to the application’s content (dashboards containing elements), a user should have at least one of the 10 roles described in the **Roles** section below.
</details>

<details>
<summary>Roles</summary>

The following roles with predefined access are available in Visma.net Insights:

1.  **Accountant**
2.  **Board member**
3.  **CFO**
4.  **Controller**
5.  **Employee**
6.  **Manager**
7.  **Sales** **Manager**
8.  **Seller**
9.  **Top** **manager**
10.  **Super user**

*   The **Accountant**, **Board member** and **Controller** have access only to the **Financial** elements in the application (**Profit & Loss**, **Balance** and **Financial KPIs**)
*   The **CFO**, **Super user** and **Top manager** roles grant access to both **Financial** and **Sales** elements, so basically all the content in the application.
*   The **Sales manager** has access only to **Profit & Loss** elements from the **Financial** area and all the elements from the **Sales** area.
*   The **Seller** gives the user access to all the **Sales** elements.
*   The **Manager** and the **Employee** are “free” **roles**. They have no default access but this can be added later.

The above predefined **access** per **role** can be later customized by the Insights **Administrator**.

Please be aware that only the **Professional user** type has by default access to the dashboards in Visma.net Insights.

The **Standard users** will need a **Professional user** to share dashboards with them so they can have content in the application (see more details on User types in the next section).
</details>

<details>
<summary>User types</summary>

In order to enforce the different **license types**, functionality is limited based upon **user types**.

The existing user types in Insights are:

*   **Standard User**
*   **Professional User**

These can be assigned only by the **Administrator** from the **Admin** module.  

The license enforcement is made in the following way:

*   The **Professional User** has access to all the functionality available in the application
*   The **Standard User** has limited access to the functionality, as described below:
    *   Can only use a dashboard shared with him by a **Professional User**.
        All the dashboards shared with **Standard Users** are automatically activated by the system.
    *   Is not able to change the content.
    *   The functionality <u>available</u> for **Standard User** is: drill-down, change x-axis, filtering time and dimensions, changing chart type and activating, deactivating, deleting a shared dashboard and also sharing a dashboard

    *   The functionality <u>not available</u> for **Standard User** is: adding new elements and dashboards, save as template, restore to original, add/remove series to/from a chart
</details>

<details>
<summary>Setup of access rights</summary>

We assume that the Partner or the Licensing department has already added the Visma.net Insights license, and that you have the role as Customer administrator.

1.  Go to the **Admin** module.
2.  On the Companies tab, select the required company.
3.  In the service list, go to Visma.net Insights.
4.  Switch the **Status** to **On** to activate the license.
5.  Click **Save and close**.
6.  Go the tab **Users and roles**.
7.  Select a user.
8.  Click on **Add access to**.
9.  Select the customer name from the list.
10.  On the row with the customer name under **Insights**, assign a user type.  
    For example, **Standard**.
11.  On the row with the company name under **Insights**, select the role you wish to assign for the respective user. For example, **Accountant**.
12.  Click **Save and close**.
</details>

<details>
<summary>Customization of access per role</summary>

The predefined access on each role is not fixed. It can be changed by the user having the **Administrator** role in Insights.

Let us say for example that the Insights **Administrator** wants to restrict the access to the **Balance sheet** elements for all the users having the **Accountant** role. Follow the steps below:

1.  From Visma.net Insights, open the **Settings** menu.

    You will be directed in the **Access per role** section.
2.  On the row with the **Accountant**, click on the categories under the **Financial** area.

    A drop-down menu will be displayed with the 3 categories: **Profit & Loss**, **Balance** and **Financial KPIs**.
3.  Deselect the **Balance** category.  

    The KPIs which belong to the **Balance sheet** - **Balance-period** and **Balance-movements** have been automatically deselected from the category **Financial KPIs**.  

4.  Click on **Save**. 

    This will add the word **Customized** next to the **Accountant** role name.  
    Also the **Financial KPIs** category will have an info icon that there are some exceptions in that category.
</details>

<details>
<summary>Customization of access per user</summary>

You as the **Administrator** can further refine the access rights on each user in part. For example, you can continue to restrict the access of a user having an **Accountant** role. You has two possibilities:

<details>
<summary>Further restrict the access on elements</summary>

You as the **Administrator** want to restrict the access of one user having the **Accountant** role to the **Payroll costs** element:

1.  Go in the **Access per user** section
2.  On the row with the respective user name, click on the categories under the **Financial** area
3.  Expand the **Profit & loss** category.
4.  Expand the **Fixed costs** sub-category.
5.  Deselect the **Payroll costs** element.
6.  Click **Save**.
    You will see that now also the **Profit & loss** category has the exception icon.
</details>
and/or

<details>
<summary>Further restrict the access on business dimensions</summary>

Please note that the list of business dimensions from the Access per user tab is not identical with the change dimension drill-down list.  

The latter contains dimensions used for data exploration like: account, some company specific dimensions (branch, currency), sales specific properties (city, country, customer, UOM) and time dimensions (days, months, quarters, years).

You as the **Administrator** can restrict the access of a user to only some values of, for example, the **Product group** business dimension:

1.  Go in the **Access per user** section
2.  On the row with the respective user name, click on the business dimensions list (the last column from left to right)
3.  Expand the desired business dimension.  
    For example **Product group**.
4.  Deselect the checkbox next to the dimension name.  
    For example **Product group**.
5.  Select the dimension value you want to allow access to.  
    For example, **Product group 1** and **Product group 2**.
6.  Click **Save**.
    You will see that now that the **Product group** business dimension has the exception icon with the message **Restriction on this Business Dimension**.
</details>
In the business dimensions list, below each dimension name there are two things:

*   A **Search** field here you can enter a dimension value and look it up
*   An informational checkbox which shows if the respective user will have access or not to the future values for that business dimension.  
    As a rule, when the business dimension name has been deselected then this checkbox will also be automatically deselected.

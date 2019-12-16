# Code Fellows ASP.NET 401 eCommerce Website Project - TINY PLANTS

## TINY PLANTS
*Authors: Karina Chen and Kyungrae Kim*

---

### Deployed Website
https://dotnet-ecommerce-tiny-plants.azurewebsites.net/

---

### About This Program
This is an eCommerce store TINY PLANTS built with ASP.NET Core's MVC and Razor Pages. The web app features a user login security system, a welcoming home page, a product page, and a product details page that allows the user to add items into cart for checkout. This web app is built to provide a satisfying shopping experience to our users.

---

### Features
#### Products
This e-commerce store sells tiny plants including cactuses, flowers, and evergreen plants that can be placed indoor. There are currently total of 10 products available on this website.
#### Claims
This web app captures claims of a user's first and last name. After a user registers a new account or logins to the site, a greeting message shows up on the top right corner of the nav bar with the user's first and last name.
#### Policies
This web app uses "AdminOnly" policy to grant Admin special access previllages to /Admin and /Inventory page. This policy has been enforced so that only Admin can control the store inventory. To test the policy, use the following credential to log into the Admin account:
    * Account: JONATHAN'S GMAIL ADDRESS (re*************@g****.com)
    * Password: Admin1234!
#### Entity Relationship Diagram
![erd](/dotnet_ECommerce/dotnet_ECommerce/wwwroot/captures/erd.png)
* Cart table has one to many relationship with CarItems table
* Order table has one to many relationship with OrderItems table
* Product table has one to many relationship with CartItems table
* Product table has one to many relationship with OrderItems table

---

### Link to Code
https://dev.azure.com/dotnet-ecommerce/_git/dotnetd9-ecommerce-karina-kyungrae?_a=contents&version=GBmaster

---

### Visuals
#### Home
##### Home - Logged Out
![home-loggedout](/dotnet_ECommerce/dotnet_ECommerce/wwwroot/captures/home-loggedout.JPG)
##### Home - Logged In (User)
![home-loggedin-user](/dotnet_ECommerce/dotnet_ECommerce/wwwroot/captures/home-loggedin-user.JPG)

#### Account
##### Register
![account-register](/dotnet_ECommerce/dotnet_ECommerce/wwwroot/captures/account-register.JPG)
##### Login
![account-login](/dotnet_ECommerce/dotnet_ECommerce/wwwroot/captures/account-login.JPG)
##### User Profile
![user-profile](/dotnet_ECommerce/dotnet_ECommerce/wwwroot/captures/user-profile.JPG)
##### Manage Orders (User)
![orders-user](/dotnet_ECommerce/dotnet_ECommerce/wwwroot/captures/orders-user.JPG)
##### Manage Order Details (User)
![order-details-user](/dotnet_ECommerce/dotnet_ECommerce/wwwroot/captures/order-details-user.JPG)

#### Shop
##### Shop
![shop](/dotnet_ECommerce/dotnet_ECommerce/wwwroot/captures/shop.JPG)
##### Shop/Product - Logged Out
![shop-product-loggedout](/dotnet_ECommerce/dotnet_ECommerce/wwwroot/captures/shop-product-loggedout.JPG)
##### Shop/Product - Logged In
![shop-product-loggedin](/dotnet_ECommerce/dotnet_ECommerce/wwwroot/captures/shop-product-loggedin.JPG)
##### Shop/Product - MiniCart
![shop-product-loggedin-minicart](/dotnet_ECommerce/dotnet_ECommerce/wwwroot/captures/shop-product-loggedin-minicart.JPG)
##### Shop/Cart (Empty)
![shop-cart-empty](/dotnet_ECommerce/dotnet_ECommerce/wwwroot/captures/shop-cart-empty.JPG)
##### Shop/Cart
![shop-cart](/dotnet_ECommerce/dotnet_ECommerce/wwwroot/captures/shop-cart.JPG)

#### Checkout
##### Checkout
![checkout](/dotnet_ECommerce/dotnet_ECommerce/wwwroot/captures/checkout.JPG)
##### Checkout/Receipt
![checkout-receipt](/dotnet_ECommerce/dotnet_ECommerce/wwwroot/captures/checkout-receipt.JPG)

#### Admin
##### Admin
![admin](/dotnet_ECommerce/dotnet_ECommerce/wwwroot/captures/admin.JPG)
##### Manage Blob
![admin-blob](/dotnet_ECommerce/dotnet_ECommerce/wwwroot/captures/admin-blob.JPG)
##### Manage Orders (Admin)
![orders-admin](/dotnet_ECommerce/dotnet_ECommerce/wwwroot/captures/orders-admin.JPG)
##### Manage Order Details (Admin)
![order-details-admin](/dotnet_ECommerce/dotnet_ECommerce/wwwroot/captures/order-details-admin.JPG)
##### Inventory
![inventory-home](/dotnet_ECommerce/dotnet_ECommerce/wwwroot/captures/inventory-home.JPG)
##### Inventory/Create
![inventory-create](/dotnet_ECommerce/dotnet_ECommerce/wwwroot/captures/inventory-create.JPG)
##### Inventory/Edit
![inventory-edit](/dotnet_ECommerce/dotnet_ECommerce/wwwroot/captures/inventory-edit.JPG)
##### Inventory/Details
![inventory-details](/dotnet_ECommerce/dotnet_ECommerce/wwwroot/captures/inventory-details.JPG)
##### Inventory/Delete
![inventory-delete](/dotnet_ECommerce/dotnet_ECommerce/wwwroot/captures/inventory-delete.JPG)

#### Email
##### Welcome New User
![send-email-welcome-new-user](/dotnet_ECommerce/dotnet_ECommerce/wwwroot/captures/welcome.JPG)
##### Order Receipt
![send-email-order-receipt](/dotnet_ECommerce/dotnet_ECommerce/wwwroot/captures/email-receipt.JPG)

---

### Resources
[Add or Remove Multiple Entities in Entity Framework](https://www.entityframeworktutorial.net/entityframework6/addrange-removerange.aspx)  
[Adding Email](https://www.learnrazorpages.com/razor-pages/tutorial/bakery/email)  
[Azure Blob storage client library v12 for .NET](https://docs.microsoft.com/en-us/azure/storage/blobs/storage-quickstart-blobs-dotnet)  
[Azure Storage CRUD Operations In MVC Using C#](https://www.c-sharpcorner.com/article/azure-storage-crud-operations-in-mvc-using-c-sharp-part-two/)  
[Handler Methods in Razor Pages](https://www.learnrazorpages.com/razor-pages/handler-methods)  
[HtmlHelper - Editor](https://www.tutorialsteacher.com/mvc/htmlhelper-editor-editorfor)  
[Model Binding](https://www.learnrazorpages.com/razor-pages/model-binding)  
[Upload files in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/mvc/models/file-uploads?view=aspnetcore-3.1)  
[Upload File In Azure Blob Storage Using ASP.NET Core](https://www.c-sharpcorner.com/article/upload-files-in-azure-blob-storage-using-asp-net-core/)

---

### Change Log
1.1: Sprint 2 Completed, Initial Submission - 03 Dec 2019  
1.0: Sprint 1 Completed, Initial Submission - 26 Nov 2019  
0.0: Project Initiated - 18 Nov 2019  

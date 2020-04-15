## Dear Mr.FrontHead , github users , and everyone ,  

###### First of all , we could tell that this should be my first try on github community , So as you can imagine guys that's can't be considered as a serious project since it's meant to be for learning purpose and i will be focusing on e-commerce concept.

# Deep-learning project:

### Deep-learning project will be written with PHP (LARAVEL FRAMEWORK) with a lil bit of Javascript and as i've mentioned above that it will an e-commerce project, However it means buying selling and tracking orders , So let's just dive into this project's life cycle real quick.

## Deep-learning's life cycle:

* Let's imagine that we have a user/customer that browses our e-commerce website so what should do/find into it ? Yes! , logical question.

* Of course he should see out there products that would be under a specific subcategory that would be actually under a specific parent category , So for sure he can choose as many as products he wants and add them right away into his own cart with the full powered rights to manage his own order add/remove and update his own order's contains in order to proceed to latest section which is checkout .. Simple as that ? No!.

### So in the previous few points up there we were talking about the users experience itself but we haven't covered yet what are we going to do for them to fit their needs.

* First we should be creating section for all our categories and link them to our child/sub categories.
  * Adding/Editing/Removing Parent category (Name - image).
  * Adding/Editing/Removing Child category (Name - image - belongs to whom!).
  * Adding/Editing/Removing a Product related to a specific Child category (Name - image - Even More images - price - an exist brand).
  * Ability to Add/Update a comment on a specific product to tell others what do you think about this product.
  
*Note that: customers don't need to login in order to create an order*

* Brands field that will contain all the available brands for all the products included in our website.
* Orders field that will handle all the orders ordered via customer and set it as activated for processes purpose.
## Administration Panel pages and modules 
* DashBoard => which will preview all the updates happened towards our database which includes:
  * If any new orders available.
  * If any new users where added.
  * All the orders ordered today and total orders.
* Products => which will contain all the available products in our website which includes:
  * Where you can add / remove / update and even preview a specific product
* Users => which will contain all the users includes:
  * permissions.
  * Credentials.
* Categories => Which will contain all the ParentCategories.
  * With the full powered authority to (Add / Remove / Update) and even preview.
* ChildCategories = > Which will be linked with a specific ParentCategory.
* Orders module => Which will contain all the orders ordered by all the customer
 * Full control to handle a specific order (Delete / Edit / Preview / change status
## User experience Pages / Modules
* Home => Which will contain all the categories and ref to their children 
 * This page should have some features such as (Latest added products , and Most viewed products)
 * a Navigation for all the available children.
* Registration => Pushing a new user to our database according to valid inputs.
* Login => Checking if the user's input required was true then go ahead.
* Products => Fetching all the products inserted into our database and bang view.
* Product-Details => Will manage to view just one product was chosen and preview all it's content and information.

*I think that's all for now ,thanks*



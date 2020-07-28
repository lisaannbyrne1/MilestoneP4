# F & V Supplies Product Sales Website

## Stream Four Project: Full Stack with Django Milestone Project
This full stack website is an e-commerce store which allows users to browse and purchase products from a fictional online store. The stores target audience is veterinary practitioners and farmers. 
There is also functionality to allow the store owner to edit, delete and update the products on the website.

### Demo
A live demo can be found <a href="https://fandvsupplies.herokuapp.com/">here.</a>

### UX
#### User stories
##### Navigation & Searching
As a shopper I want to be able to view of list of all products sold on the site.

As a shopper I want to be able to view the product details including price.

As a shopper I want to be able to easily see the total of my shopping cart. 

As a shopper I want to be able to search for products by category, name or description. 

##### Account & Checkout
As a site user I want to be able to register a new account and receive a confirmation email of my registration.

As a site user I want to be able edit my account details easily.

As a site user I want to be able to see a list of products I have purchased.

As a site user I want to be able to purchase products without setting up an account. 

##### Store Administrator
As the store administrator I want to be able to edit products.

As the store administrator I want to be able to delete products.

As the store administrator I want to be able to add new products.

#### Strategy
The goal of this website is to allow farmers and vets to easily purchase necessary supplies without having to come into the store. It also gives them the opportunity to browse the products in store before their visit. The navigation is clear to assist them in finding what products they want quickly and easily. The various search areas should allow for additional quick searches. 

#### Scope
The store is aimed at farmers and vets but also anyone who needs farming related products.  The navigation is clear and therefore should allow for any interested user find the products they are looking for. 

#### Structure
The structure of this site is set up using apps to handle the various elements.  For example, the bag app allows for users to add products to their bag.  The checkout app then allows the user to purchase the products.  The profiles app allows the user to set up and manage their profile.  The products app allows for the user to view the products available and also allows the site administrator to edit, add and delete products from the site. 
The layout of this site starts with a landing page which includes links to the various menu options across the site and also access to the products, shopping bag and account.  The landing page provides all the information that the user should need to navigate the site. 

#### Skeleton
Desktop and mobile wireframes have been created <a href="https://github.com/lisaannbyrne1/ MilestoneP4-F-V_Supplies/blob/master/static/wireframe/wireframes.pdf">click here</a>

#### Surface
The colour scheme of the site is white and black. The home page includes a large jumbotron farming image to represent the target audiences of the site. The colour scheme was chosen to form a minimalist and uniform look through out the site. 

#### Technologies
* HTML
* CSS/Bootstrap (4.4.1)
* JavaScript/jQuery
* Python + Flask
* Django
* Stripe payments



### Features
The features on this site include the ability for users to purchase products through a checkout app.  The users have the option of purchasing with or without an account. If the user creates an account, they will be able to view their purchase history on their profile and update their delivery details. Another feature of the site is that it allows the owner to log in using a superuser account and add, edit, and remove products from the site.  

#### Features Left to Implement
In the future, I would like to include a quick link to add to cart from the products page. I would also like to implement a quantity remaining notification for products on the site. As this site is fictional, I have left the links for the social media blank but should this become a real site someday these socials can be populated. Finally, a feature left to add would be to increase the number of products that is available online via the site. 

#### Testing
This site was tested against criteria set out in the user stories and the criteria was met in each case. While testing I noticed that the footer was appearing over the contents at the bottom of each page, to fix this I needed to add a bottom margin to the container. During testing I noticed the images were slow to load and very large, I resized the images using tinypng.com. During testing of registration of new accounts, it was highlighted that when I originally set up my Django site using the name example.com I had forgotten to change it.  I was able to change it in the Django admin panel to the name of my site. Finally, I tested the site on mobile and on a various other website browsers a small number of small changes were required to the media queries as a result of these tests. 

#### Deployment
The website was deployed to Heroku from GitHub and static files were stored on AWS S3.  As part of set up on AWS I had to generate a security policy for the bucket to be accessed. Static files including images were stored on AWS and accessed by Heroku through the build, it will search my apps and project folders for static files.  Images are also stored on AWS through direct upload to AWS. 

### Credits
#### Content 
The data contents of this app and database is fictional for example purposes.

#### Media
The images for this site were obtained from google searches. 

#### Acknowledgements
I received inspiration from several sources for this project, they included feedback from users both internal and external to my current employer.   I also took inspiration for this project from areas covered in the course and in the mini projects. 

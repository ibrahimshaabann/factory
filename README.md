# documentation 
## Project idea:
we have a big factory that manufuctures glass with many depatments: e.g. decoration, car glasses, glasses for buildings and any other types of glasses. we have 
different roles in our project and each role has different permissions and access.

## Roles
### Levels and roles:

1- Manager levels (admin dashboard):
  a - super : has the access to all tables in the systtem and has the access to do all actions.
    - super user or admin can have accsess to all of the factory branches and their data.
  b - branch manager:
    - branch manager has access only to his branch, e.g. assiut branch manager hass access to factory branch in assiut
    - This will be done based on location based-data retrieval with google analytics.
  c - employee:
    - employee has different roles

- The factory manager aim is from partioning this role is to know the type of his customer either it is an engineering office, (dealer) or a normal customer
2- Customers:
  a- Engineering office manager:
      -can request glass material for a certain buliding

  b- Dealer of glass material: 
    - dealer can request a large a quantity of glass from our factory
    
  c - Normal customer:
    1- usually,, normal customer can request for a smaal nuumber of our products.  
    2- customer should have a customer support in our application 
      - we need a simple ui ux design for the customer to contact the factory staff or customer service.
      - redirect for whatsapp and messenger chats from our site
      - Product request with the customer info (email, phone_numbe, Request product, full_name, closest branch to the customer)
      - Customer has no online payment, he can only pay in the closest branch


## Requirements:

### 1- Our factory Products:
1- Each product has a related category like , car glasses, glasses for buildings and any other types of glasses 
2- Each products has multiple stages of production for manufacturing
3- The responsible user for identifying the stages of production is still unknown! but of courese it will be of the previously provided manager levels .
4- The customer can view the stages of production or manufacturing for his product that he owns or purchased
5- Product (virtual, estimated or approcimate price) price wich will be accsseible to employee or manager levels
6- Actual selling price. That's the final and actual price of the product which the customer will purchase.

### 2-  categories 
      - Reviewing all available categories of products and products available in each category

### 3- Managing Personal account or account settings 
 
### 4- Payment 
  - Payment is allowable to one of all customer-level users ( Engineering office manager,  Dealer of glass material, normal customer) 
  - Payment until now in only allowable from the branch. 

### 5- Analytics in admin dashboard:
    -  The location where our customers has logged into our system.
    -  The branch with most customers
    -  The government with most customers
    -  Most Requested product
    -  Most requested category
    -  Top customers role : This means Top customer role requesting our products.
    -  We can apply the down criteria for the previous analytics 


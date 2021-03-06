![CF](http://i.imgur.com/7v5ASc8.png) LAB
=================================================

## HTTP and REST

### Author: Erin Trainor

### Links and Resources
* [pull request](http://xyz.com)
* [front-end](https://codesandbox.io/s/w638oyk7o8)

#### Documentation
* [swagger](http://xyz.com) (API assignments only)

### Setup

#### Terminal Commands to Manipulate the API
* Categories
  * `/categories`  
    * `GET` - http GET :3000/categories
    * `POST` - echo '{"name":"Footwear", "display_name":"Footwear", "description":"Unusual things to wear on your feet"}' | http POST :3000/categories
    * `POST` - echo '{"name":"Pet", "display_name":"Pet Products", "description":"Strang things your pet will love"}' | http POST :3000/categories
  * `/categories/:id/` 
    * `PUT` - echo '{"name":"Footwear", "display_name":"Shoes", "description":"Unusual thingsto wear on your feet", "_id":"1}' | http PUT :3000/categories/1
    * `DELETE` - http DELETE :3000/categories/1
* Products
  * `/products`  
    * `GET` - http GET :3000/products
    * `POST` - echo '{"name":"Bread Slippers", "display_name":"Loafers", "description":"When you want your feet to look like a loaf of bread", "category":"Footwear"}' | http POST :3000/products
    * `POST` - echo '{"name":"Dog Socks", "display_name":"Paw Grip Socks", "description":"For when you want your dog to be able to run on slick surfaces", "category":"Pet"}' | http POST :3000/products
  * `/products/:id/` 
    * `PUT` - echo '{"name":"Dog Socks", "display_name":"Paw Grip Socks", "description":"For when you want your dog to be able to dance on slick surfaces", "category":"Pet", "_id":2}' | http PUT :3000/products/2
    * `DELETE` - http DELETE :3000/products/2
  
#### UML
Link to an image of the UML for your application and response to events

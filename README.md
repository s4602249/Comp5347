# COMP5347 (The website of SellPhone)

It is an eCommerce web application that allows user to search, review, checkout and comment on the phone listing.
According to the diferent web pages, it contains four main pages which is Main page, Signin/Signup page, Checkout page and User page.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 

### Prerequisites

* Install Node.js on https://nodejs.org/en/

* Install MongoDBCompass on https://www.mongodb.com/products/compass

* Install Postman on https://www.postman.com/


### Installing

* Installing NPM modules on server side

Execute these commands from the project directory

```
cd server
npm install
```

* Installing Live server extension. If you are using Visual Studio Code, you can click **Extensions** on right panel and search Live server and install.

### Running the app

* Import two json file (userlist and phonelisting) by using MongoDBCompass

* Opening back end server first

```
cd server
node app.js
```

* Run http://localhost:3000/api/phone/changeUrl through **get** method on Postman to change the image Url on database

* Find **views** folder under **client** folder and right click on SignPage.html or MainPage.html and **Open with Live Server (Reminder: The port used in front end should be 5501)**

## Contributing

* **LanXin Zheng** - front end deisgn of Main page and Checkout page
* **Ruoyao Tan** - front end deisgn of Signin/Signup page and User page
* **Xufeng Zheng** - back end implementation of Main page and Signin/Signup page 
* **Ning Yang** - back end implementation of Checkout page and User page
(add the item to cart backend logic and file-upload frontend+backend logic)

See also the list of [contributors](https://github.sydney.edu.au/COMP5347-2022/WebDev-11/graphs/contributors) who participated in this project.

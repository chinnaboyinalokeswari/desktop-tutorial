---
title: "E-Commerce Application Using HTML CSS JS"
seoTitle: "web development project"
seoDescription: "Build e-commerce application using HTML,CSS,JAVA SCRIPT"
datePublished: Thu May 18 2023 07:17:42 GMT+0000 (Coordinated Universal Time)
cuid: clhssur1e03etssnv1inlg8r4
slug: e-commerce-application-using-html-css-js
canonical: https://hashnode.com/preview/63a722eeb1011ed9ec6cebcb
cover: https://cdn.hashnode.com/res/hashnode/image/stock/unsplash/TamMbr4okv4/upload/6f4b1ae13394d2fb99674867edad8877.jpeg
tags: techworld

---

let us discuss about short summary about my project

#### **Introduction:**

This project is about an e-commerce website where a user can do shopping with a seamless experience.

A user can choose a product as per his choice

He can filter the products by size as well as by the color he wants.

You can customize this project’s animation as well as logic as per requirement.

It’s one of the major projects you can use for your personal use as well as to present in your college.

#### **Structure of Project:**

The code begins with a tag that contains two child tags: one for the main content of the page, and another for the navigation.

 The first thing you see is a pair of tags.

 The first one displays a name of website i.e [**EcommerceStore.com**](http://EcommerceStore.com), while the second one displays a search icon.

 This will be used to help users find what they’re looking for on the site.

 Inside of that holds all of the content on the page, you’ll see a series of paragraphs.

 The first paragraph contains information about how to purchase items from this store.

 It includes details like product categories and prices.

 The next paragraph lists all of the available products in each category.

 Each product has its own row, and there are images associated with each item so that users can better understand what they’re buying.

You also include links to more detailed descriptions if needed.

Finally, at the bottom of this paragraph is a link to view additional product information **(such as dimensions and materials).**

Next comes a section where users can search for products by keyword or phrase.

The code creates a div with the class ***navItem,*** which will house all of the navigation for our ecommerce store.

Within this div, we have two elements: a ***search input*** and an icon for our search bar.

The code within the search input will allow users to enter text into the form and it will be autofilled with the current page’s title.

The icon will be used as a placeholder for our search bar and it will dynamically change depending on whether or not there is any content in our search input.

Finally, we have created a div with the class ***navItem*** which will house all of our navigation.

Within this div, we have created a heading titled “Ecommerce Store” and beneath this heading

**JavaScript Logic :**

The code starts by creating an ***array*** of objects called products .

Each object in the products array will contain information about a different product.

The first object in the products array is called choosen Product .

This object will hold the information about the product that was chosen by the user (in this case, it’s Air Jordan).

Next, we need to get hold of all of the information about choosen Product .

We do this by using ***document.querySelectorAll() .***

This method takes two arguments: The first is a selector (in this case, ***“.productTitle”)*** and the second is a list of strings (in this case, “.color”).

We then use ***forEach()*** to loop through all of the ***menuItems*** in our document.

Each time around the loop, we’ll add an event listener to each item so that we can track when it’s clicked.

In this case, when someone clicks on one of our menu Items , we want to run a function called ***analyze()*** .

This function will take three arguments: The first is choosen Product , which we’ve already obtained from earlier; secandly, current Product Img , which is our image pointer for displaying what’s currently being displayed on our screen; and finally, current

The code creates a slider with six different products.

Each product has an id, title, price, and colors.

The code also creates a menu item for each product.

When the user clicks on any of the menu items, the code will call a function that will take care of the rest.

The first thing that the function does is find the product that was clicked on.

This is done by using the index variable which refers to the particular menu item that was clicked on.

Once it finds the product, it sets up some event handlers for it so that when it is clicked again or when something else happens in the slider, it will be triggered.

The event handlers are used to change some variables in regard to each of the products.

#### **Source Code**

##### **index.html**

```html
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=League+Spartan:wght@500&family=Nunito&family=Palanquin+Dark:wght@500&family=Roboto+Slab:wght@700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
    <title>Nike Store</title>
</head>

<body>
    <nav id="nav">
        <div class="navTop">
            <div class="navItem">
                <h2>EcommerceStore.com</h2>
                <!-- <img decoding="async" src="./img/sneakers.png" alt=""> -->
            </div>
            <div class="navItem">
                <div class="search">
                    <input type="text" placeholder="Search..." class="searchInput">
                    <img decoding="async" loading="lazy" src="./img/search.png" width="20" height="20" alt="" class="searchIcon">
                </div>
            </div>
            <div class="navItem">
                <span class="limitedOffer">Limited Offer!</span>
            </div>
        </div>
        <div class="navBottom">
            <h3 class="menuItem">AIR FORCE</h3>
            <h3 class="menuItem">JORDAN</h3>
            <h3 class="menuItem">BLAZER</h3>
            <h3 class="menuItem">CRATER</h3>
            <h3 class="menuItem">HIPPIE</h3>
        </div>
    </nav>
    <div class="slider">
        <div class="sliderWrapper">
            <div class="sliderItem">
                <img decoding="async" src="./img/air.png" alt="" class="sliderImg" id="firsts">
                <div class="sliderBg"></div>
                <h1 class="sliderTitle">AIR FORCE</br> NEW</br> SEASON</h1>
                <h2 class="sliderPrice">Rs.1999</h2>
                <a href="#product">
                    <button class="buyButton">BUY NOW!</button>
                </a>
            </div>
            <div class="sliderItem">
                <img decoding="async" src="./img/jordan.png" alt="" class="sliderImg" id="jordan">
                <div class="sliderBg"></div>
                <h1 class="sliderTitle">AIR JORDAN</br> NEW</br> SEASON</h1>
                <h2 class="sliderPrice">Rs 1149</h2>
                <a href="#product">
                    <button class="buyButton">BUY NOW!</button>
                </a>
            </div>
            <div class="sliderItem">
                <img decoding="async" src="./img/blazer.png" alt="" class="sliderImg" id="thirds">
                <div class="sliderBg"></div>
                <h1 class="sliderTitle">BLAZER</br> NEW</br> SEASON</h1>
                <h2 class="sliderPrice">Rs 2100</h2>
                <a href="#product">
                    <button class="buyButton">BUY NOW!</button>
                </a>
            </div>
            <div class="sliderItem">
                <img decoding="async" src="./img/crater.png" alt="" class="sliderImg" id="crater">
                <div class="sliderBg"></div>
                <h1 class="sliderTitle">CRATER</br> NEW</br> SEASON</h1>
                <h2 class="sliderPrice">Rs 2999</h2>
                <a href="#product">
                    <button class="buyButton">BUY NOW!</button>
                </a>
            </div>
            <div class="sliderItem">
                <img decoding="async" src="./img/hippie.png" alt="" class="sliderImg">
                <div class="sliderBg"></div>
                <h1 class="sliderTitle">HIPPIE</br> NEW</br> SEASON</h1>
                <h2 class="sliderPrice">Rs 999</h2>
                <a href="#product">
                    <button class="buyButton">BUY NOW!</button>
                </a>
            </div>
        </div>
    </div>

    <div class="features">
        <div class="feature">
            <img decoding="async" src="./img/shipping.png" alt="" class="featureIcon">
            <span class="featureTitle">FREE SHIPPING</span>
            <span class="featureDesc">Free worldwide shipping on all orders.</span>
        </div>
        <div class="feature">
            <img decoding="async" class="featureIcon" src="./img/return.png" alt="">
            <span class="featureTitle">30 DAYS RETURN</span>
            <span class="featureDesc">No question return and easy refund in 14 days.</span>
        </div>
        <div class="feature">
            <img decoding="async" class="featureIcon" src="./img/gift.png" alt="">
            <span class="featureTitle">GIFT CARDS</span>
            <span class="featureDesc">Buy gift cards and use coupon codes easily.</span>
        </div>
        <div class="feature">
            <img decoding="async" class="featureIcon" src="./img/contact.png" alt="">
            <span class="featureTitle">CONTACT US!</span>
            <span class="featureDesc">Keep in touch via email and support system.</span>
        </div>
    </div>

    <div class="product" id="product">
        <img decoding="async" src="./img/air.png" alt="" class="productImg">
        <div class="productDetails">
            <h1 class="productTitle">AIR FORCE</h1>
            <h2 class="productPrice">Rs 1999</h2>
            <p class="productDesc">Lorem ipsum dolor sit amet consectetur impal adipisicing elit. Alias assumenda
                dolorum
                doloremque sapiente aliquid aperiam.</p>
            <div class="colors">
                <div class="color"></div>
                <div class="color"></div>
            </div>
            <div class="sizes">
                <div class="size">42</div>
                <div class="size">43</div>
                <div class="size">44</div>o
            </div>
            <button class="productButton">BUY NOW!</button>
        </div>
        <div class="payment">
            <h1 class="payTitle">Personal Information</h1>
            <label>Name and Surname</label>
            <input type="text" placeholder="John Doe" class="payInput">
            <label>Phone Number</label>
            <input type="text" placeholder="+1 234 5678" class="payInput">
            <label>Address</label>
            <input type="text" placeholder="Elton St 21 22-145" class="payInput">
            <h1 class="payTitle">Card Information</h1>
            <div class="cardIcons">
                <img decoding="async" src="./img/visa.png" width="40" alt="" class="cardIcon">
                <img decoding="async" src="./img/master.png" alt="" width="40" class="cardIcon">
            </div>
            <input type="password" class="payInput" placeholder="Card Number">
            <div class="cardInfo">
                <input type="text" placeholder="mm" class="payInput sm">
                <input type="text" placeholder="yyyy" class="payInput sm">
                <input type="text" placeholder="cvv" class="payInput sm">
            </div>
            <button class="payButton">Checkout!</button>
            <span class="close">X</span>
        </div>
    </div>
    <div class="gallery">
        <div class="galleryItem">
            <h1 class="galleryTitle">Be Yourself!</h1>
            <img decoding="async" src="https://images.pexels.com/photos/13159244/pexels-photo-13159244.jpeg"
                alt="" class="galleryImg">
        </div>
        <div class="galleryItem">
            <img decoding="async" src="https://images.pexels.com/photos/2982100/pexels-photo-2982100.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
                alt="" class="galleryImg">
            <h1 class="galleryTitle">This is the First Day of Your New Life</h1>
        </div>
        <div class="galleryItem">
            <h1 class="galleryTitle">Just Do it!</h1>
            <img decoding="async" src="https://images.pexels.com/photos/1018911/pexels-photo-1018911.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
                alt="" class="galleryImg">
        </div>
    </div>
    <div class="newSeason">
        <div class="nsItem">
            <img decoding="async" src="https://images.pexels.com/photos/34514/spot-runs-start-la.jpg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
                alt="" class="nsImg">
        </div>
        <div class="nsItem">
            <h3 class="nsTitleSm">WINTER NEW ARRIVALS</h3>
            <h1 class="nsTitle">New Season</h1>
            <h1 class="nsTitle">New Collection</h1>
            <a href="#nav">
                <button class="nsButton">CHOOSE YOUR STYLE</button>
            </a>
        </div>
        <div class="nsItem">
            <img decoding="async" src="https://images.pexels.com/photos/7856965/pexels-photo-7856965.jpeg?auto=compress&cs=tinysrgb&dpr=2&w=500"
                alt="" class="nsImg">
        </div>
    </div>
    <footer>
        <div class="footerLeft">
            <div class="footerMenu">
                <h1 class="fMenuTitle">About Us</h1>
                <ul class="fList">
                    <li class="fListItem">Company</li>
                    <li class="fListItem">Contact</li>
                    <li class="fListItem">Careers</li>
                    <li class="fListItem">Affiliates</li>
                    <li class="fListItem">Stores</li>
                </ul>
            </div>
            <div class="footerMenu">
                <h1 class="fMenuTitle">Useful Links</h1>
                <ul class="fList">
                    <li class="fListItem">Support</li>
                    <li class="fListItem">Refund</li>
                    <li class="fListItem">FAQ</li>
                    <li class="fListItem">Feedback</li>
                    <li class="fListItem">Stories</li>
                </ul>
            </div>
            <div class="footerMenu">
                <h1 class="fMenuTitle">Products</h1>
                <ul class="fList">
                    <li class="fListItem">Air Force</li>
                    <li class="fListItem">Air Jordan</li>
                    <li class="fListItem">Blazer</li>
                    <li class="fListItem">Crater</li>
                    <li class="fListItem">Hippie</li>
                </ul>
            </div>
        </div>
        <div class="footerRight">
            <div class="footerRightMenu">
                <h1 class="fMenuTitle">Subscribe to our newsletter</h1>
                <div class="fMail">
                    <input type="text" placeholder="your@email.com" class="fInput">
                    <button class="fButton">Join!</button>
                </div>
            </div>
            <div class="footerRightMenu">
                <h1 class="fMenuTitle">Follow Us</h1>
                <div class="fIcons">
                    <img decoding="async" src="./img/facebook.png" alt="" class="fIcon">
                    <img decoding="async" src="./img/twitter.png" alt="" class="fIcon">
                    <img decoding="async" src="./img/instagram.png" alt="" class="fIcon">
                    <img decoding="async" src="./img/whatsapp.png" alt="" class="fIcon">
                </div>
            </div>
            <div class="footerRightMenu">
                <span class="copyright">@John Doe. All rights reserved. 2022.</span>
            </div>
        </div>
    </footer>
    <script src="./app.js"></script>
</body>

</html>
```

##### **style.css**

```css
html {
  scroll-behavior: smooth;
  font-family: 'League Spartan', sans-serif;
font-family: 'Nunito', sans-serif;
font-family: 'Palanquin Dark', sans-serif;
font-family: 'Roboto Slab', serif;

}

body {
  font-family: "Lato", sans-serif;
  padding: 0;
  margin: 0;
}

nav {
  /* background-color: #111; */
  background-color: #232c5b;
  color: white;
  padding: 20px 50px;
}

.navTop {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.search {
  display: flex;
  align-items: center;
  background-color: gray;
  padding: 10px 20px;
  border-radius: 10px;
}

.searchInput {
  border: none;
  background-color: transparent;
}

.searchInput::placeholder {
  color: lightgray;
}

.limitedOffer {
  font-size: 20px;
  border-bottom: 2px solid rgb(194, 40, 156);
  cursor: pointer;
}

.navBottom {
  display: flex;
  align-items: center;
  justify-content: center;
}

.menuItem {
  margin-right: 50px;
  cursor: pointer;
  color: lightgray;
  font-weight: 400;
}

.slider {
  background: url(https://images.pexels.com/photos/7078622/pexels-photo-7078622.jpeg?auto=compress&cs=tinysrgb&w=600);
  /* background: url("https://images.unsplash.com/photo-1604147495798-57beb5d6af73?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2370&q=80"); */
  clip-path: polygon(0 0, 100% 0, 100% 100%, 0 85%);
  overflow: hidden;
}

.sliderWrapper {
  display: flex;
  width: 500vw;
  transition: all 1.5s ease-in-out;
}


.sliderItem {
  width: 100vw;
  display: flex;
  align-items: center;
  justify-content: center;
  position: relative;
}

.sliderBg {
  width: 750px;
  height: 750px;
  border-radius: 50%;
  position: absolute;
}

.sliderImg {
  z-index: 1;
}
#firsts{
  width: 60rem;
}
#jordan{
  width:50rem;
  transform: rotate(20deg);
}
#thirds{
  width: 50rem;
  transform: rotate(20deg);
  /* filter: invert(100%); */
}
#crater{
  width: 50rem;
}

.sliderTitle {
  position: absolute;
  top: 10%;
  right: 10%;
  font-size: 60px;
  font-weight: 900;
  text-align: center;
  color: rgb(44, 182, 32);
  z-index: 1;
}

.sliderPrice {
  position: absolute;
  top: 10%;
  left: 10%;
  font-size: 60px;
  font-weight: 300;
  text-align: center;
  color: white;
  border: 1px solid gray;
  z-index: 1;
}

.buyButton {
  position: absolute;
  top: 50%;
  right: 10%;
  font-size: 30px;
  font-weight: 900;
  color: white;
  border: 1px solid gray;
  background-color: black;
  z-index: 1;
  cursor: pointer;
}

.buyButton:hover {
  background-color: white;
  color: black;
}

.sliderItem:nth-child(1) .sliderBg {
  background-color: #e283ce;
}
.sliderItem:nth-child(2) .sliderBg {
  background-color: rebeccapurple;
}
.sliderItem:nth-child(3) .sliderBg {
  background-color: teal;
}
.sliderItem:nth-child(4) .sliderBg {
  background-color: cornflowerblue;
}
.sliderItem:nth-child(5) .sliderBg {
  background-color: rgb(124, 115, 80);
}

.sliderItem:nth-child(1) .sliderPrice {
  color: #369e62;
}
.sliderItem:nth-child(2) .sliderPrice {
  color: white;
}
.sliderItem:nth-child(3) .sliderPrice {
  color: teal;
}
.sliderItem:nth-child(4) .sliderPrice {
  color: cornflowerblue;
}
.sliderItem:nth-child(5) .sliderPrice {
  color: cornsilk;
}

.features {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 50px;
}

.feature {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
}

.featureIcon {
  width: 50px;
  height: 50px;
}

.featureTitle {
  font-size: 20px;
  font-weight: 600;
  margin: 20px;
}

.featureDesc {
  color: gray;
  width: 50%;
  height: 100px;
}

.product {
  height: 100vh;
  background-color: rgb(107, 101, 101);
  position: relative;
  clip-path: polygon(0 15%, 100% 0, 100% 100%, 0% 100%);
}

.payment {
  width: 500px;
  height: 500px;
  background-color: white;
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  margin: auto;
  padding: 10px 50px;
  display: none;
  flex-direction: column;
  -webkit-box-shadow: 0px 0px 13px 2px rgba(0, 0, 0, 0.3);
  box-shadow: 0px 0px 13px 2px rgba(0, 0, 0, 0.3);
}

.payTitle {
  font-size: 20px;
  color: lightgray;
}

label {
  font-size: 14px;
  font-weight: 300;
}

.payInput {
  padding: 10px;
  margin: 10px 0px;
  border: none;
  border-bottom: 1px solid gray;
}

.payInput::placeholder {
  color: rgb(163, 163, 163);
}

.cardIcons {
  display: flex;
}

.cardIcon {
  margin-right: 10px;
}

.cardInfo {
  display: flex;
  justify-content: space-between;
}

.sm {
  width: 30%;
}

.payButton {
  position: absolute;
  height: 40px;
  bottom: -40;
  width: 100%;
  left: 0;
  -webkit-box-shadow: 0px 0px 13px 2px rgba(0, 0, 0, 0.3);
  box-shadow: 0px 0px 13px 2px rgba(0, 0, 0, 0.3);
  background-color: #369e62;
  color: white;
  border: none;
  cursor: pointer;
}

.close {
  width: 20px;
  height: 20px;
  position: absolute;
  background-color: gray;
  color: white;
  top: 10px;
  right: 10px;
  display: flex;
  align-items: center;
  justify-content: center;
  cursor: pointer;
  padding: 2px;
}

.productImg {
  width: 50%;
  margin-top: 6rem;
}

.productDetails {
  position: absolute;
  top: 10%;
  right: 0;
  width: 40%;
  padding: 50px;
}

.productTitle {
  font-size: 75px;
  font-weight: 900;
}

.productDesc {
  font-style: 24px;
  color: rgb(241, 234, 234);
}

.colors,
.sizes {
  display: flex;
  margin-bottom: 20px;
}

.color {
  width: 32px;
  height: 32px;
  border-radius: 5px;
  background-color: rgb(255, 247, 247);
  margin-right: 10px;
  cursor: pointer;
}

.color:last-child {
  background-color: darkblue;
}

.size {
  padding: 5px 20px;
  border: 1px solid black;
  margin-right: 10px;
  cursor: pointer;
  font-size: 20px;
}

.productButton {
  float: right;
  padding: 10px 20px;
  background-color: black;
  color: white;
  font-weight: 600;
  cursor: pointer;
}

.productButton:hover {
  background-color: white;
  color: black;
}

.gallery {
  padding: 50px;
  display: flex;
}

.galleryItem {
  flex: 1;
  padding: 50px;
}

.galleryImg {
  width: 100%;
}

.newSeason {
  display: flex;
}

.nsItem {
  flex: 1;
  background-color: black;
  color: white;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-align: center;
}

.nsImg {
  width: 100%;
  height: 500px;
}

.nsTitle {
  font-size: 40px;
}

.nsButton {
  padding: 15px;
  font-weight: 600;
  cursor: pointer;
}

footer {
  display: flex;
}

.footerLeft {
  flex: 2;
  display: flex;
  justify-content: space-between;
  padding: 50px;
}

.fMenuTitle {
  font-size: 16px;
}

.fList {
  padding: 0;
  list-style: none;
}

.fListItem {
  margin-bottom: 10px;
  color: gray;
  cursor: pointer;
}

.footerRight {
  flex: 1;
  padding: 50px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}

.fInput {
  padding: 5px;
}

.fButton {
  padding: 5px;
  background-color: black;
  color: white;
}

.fIcons{
  display: flex;
}

.fIcon{
  width: 20px;
  height: 20px;
  margin-right: 10px;
}

.copyright{
  font-weight: 300;
  font-size: 14px;
}

@media screen and (max-width:480px) {
  nav{
    padding: 20px;
  }

  .search{
    display: none;
  }

  .navBottom{
    flex-wrap: wrap;
  }

  .menuItem{
    margin: 20px;
    font-weight: 700;
    font-size: 20px;
  }

  .slider{
    clip-path: none;
  }

  .sliderImg{
    width: 90%;
  }

  .sliderBg{
    width: 100%;
    height: 100%;
  }

  .sliderTitle{
    display: none;
  }

  .sliderPrice{
    top: unset;
    bottom: -50;
    left: 0;
    background-color: lightgrey;
  }

  .buyButton{
    right: 0;
    top: 0;
  }

  .features{
    flex-direction: column;
  }

  .product{
    clip-path: none ;
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .productImg{
    width: 80%;
  }

  .productDetails{
    width: 100%;
    padding: 0;
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    position: relative;
    top: 0;
  }

  .productTitle{
    font-size: 50px;
    margin: 0;
  }

  .gallery{
    display: none;
  }

  .newSeason{
    flex-direction: column;
  }

  .nsItem:nth-child(2){
    padding: 50px;
  }
Source Code
index.html
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=League+Spartan:wght@500&family=Nunito&family=Palanquin+Dark:wght@500&family=Roboto+Slab:wght@700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
    <title>Nike Store</title>
</head>

<body>
    <nav id="nav">
        <div class="navTop">
            <div class="navItem">
                <h2>EcommerceStore.com</h2>
                <!-- <img decoding="async" src="./img/sneakers.png" alt=""> -->
            </div>
            <div class="navItem">
                <div class="search">
                    <input type="text" placeholder="Search..." class="searchInput">
                    <img decoding="async" loading="lazy" src="./img/search.png" width="20" height="20" alt="" class="searchIcon">
                </div>
            </div>
            <div class="navItem">
                <span class="limitedOffer">Limited Offer!</span>
            </div>
        </div>
        <div class="navBottom">
            <h3 class="menuItem">AIR FORCE</h3>
            <h3 class="menuItem">JORDAN</h3>
            <h3 class="menuItem">BLAZER</h3>
            <h3 class="menuItem">CRATER</h3>
            <h3 class="menuItem">HIPPIE</h3>
        </div>
    </nav>
    <div class="slider">
        <div class="sliderWrapper">
            <div class="sliderItem">
                <img decoding="async" src="./img/air.png" alt="" class="sliderImg" id="firsts">
                <div class="sliderBg"></div>
                <h1 class="sliderTitle">AIR FORCE</br> NEW</br> SEASON</h1>
                <h2 class="sliderPrice">Rs.1999</h2>
                <a href="#product">
                    <button class="buyButton">BUY NOW!</button>
                </a>
            </div>
            <div class="sliderItem">
                <img decoding="async" src="./img/jordan.png" alt="" class="sliderImg" id="jordan">
                <div class="sliderBg"></div>
                <h1 class="sliderTitle">AIR JORDAN</br> NEW</br> SEASON</h1>
                <h2 class="sliderPrice">Rs 1149</h2>
                <a href="#product">
                    <button class="buyButton">BUY NOW!</button>
                </a>
            </div>
            <div class="sliderItem">
                <img decoding="async" src="./img/blazer.png" alt="" class="sliderImg" id="thirds">
                <div class="sliderBg"></div>
                <h1 class="sliderTitle">BLAZER</br> NEW</br> SEASON</h1>
                <h2 class="sliderPrice">Rs 2100</h2>
                <a href="#product">
                    <button class="buyButton">BUY NOW!</button>
                </a>
            </div>
            <div class="sliderItem">
                <img decoding="async" src="./img/crater.png" alt="" class="sliderImg" id="crater">
                <div class="sliderBg"></div>
                <h1 class="sliderTitle">CRATER</br> NEW</br> SEASON</h1>
                <h2 class="sliderPrice">Rs 2999</h2>
                <a href="#product">
                    <button class="buyButton">BUY NOW!</button>
                </a>
            </div>
            <div class="sliderItem">
                <img decoding="async" src="./img/hippie.png" alt="" class="sliderImg">
                <div class="sliderBg"></div>
                <h1 class="sliderTitle">HIPPIE</br> NEW</br> SEASON</h1>
                <h2 class="sliderPrice">Rs 999</h2>
                <a href="#product">
                    <button class="buyButton">BUY NOW!</button>
                </a>
            </div>
        </div>
    </div>

    <div class="features">
        <div class="feature">
            <img decoding="async" src="./img/shipping.png" alt="" class="featureIcon">
            <span class="featureTitle">FREE SHIPPING</span>
            <span class="featureDesc">Free worldwide shipping on all orders.</span>
        </div>
        <div class="feature">
            <img decoding="async" class="featureIcon" src="./img/return.png" alt="">
            <span class="featureTitle">30 DAYS RETURN</span>
            <span class="featureDesc">No question return and easy refund in 14 days.</span>
        </div>
        <div class="feature">
            <img decoding="async" class="featureIcon" src="./img/gift.png" alt="">
            <span class="featureTitle">GIFT CARDS</span>
            <span class="featureDesc">Buy gift cards and use coupon codes easily.</span>
        </div>
        <div class="feature">
            <img decoding="async" class="featureIcon" src="./img/contact.png" alt="">
            <span class="featureTitle">CONTACT US!</span>
            <span class="featureDesc">Keep in touch via email and support system.</span>
        </div>
    </div>

    <div class="product" id="product">
        <img decoding="async" src="./img/air.png" alt="" class="productImg">
        <div class="productDetails">
            <h1 class="productTitle">AIR FORCE</h1>
            <h2 class="productPrice">Rs 1999</h2>
            <p class="productDesc">Lorem ipsum dolor sit amet consectetur impal adipisicing elit. Alias assumenda
                dolorum
                doloremque sapiente aliquid aperiam.</p>
            <div class="colors">
                <div class="color"></div>
                <div class="color"></div>
            </div>
            <div class="sizes">
                <div class="size">42</div>
                <div class="size">43</div>
                <div class="size">44</div>o
            </div>
            <button class="productButton">BUY NOW!</button>
        </div>
        <div class="payment">
            <h1 class="payTitle">Personal Information</h1>
            <label>Name and Surname</label>
            <input type="text" placeholder="John Doe" class="payInput">
            <label>Phone Number</label>
            <input type="text" placeholder="+1 234 5678" class="payInput">
            <label>Address</label>
            <input type="text" placeholder="Elton St 21 22-145" class="payInput">
            <h1 class="payTitle">Card Information</h1>
            <div class="cardIcons">
                <img decoding="async" src="./img/visa.png" width="40" alt="" class="cardIcon">
                <img decoding="async" src="./img/master.png" alt="" width="40" class="cardIcon">
            </div>
            <input type="password" class="payInput" placeholder="Card Number">
            <div class="cardInfo">
                <input type="text" placeholder="mm" class="payInput sm">
                <input type="text" placeholder="yyyy" class="payInput sm">
                <input type="text" placeholder="cvv" class="payInput sm">
            </div>
            <button class="payButton">Checkout!</button>
            <span class="close">X</span>
        </div>
    </div>
    <div class="gallery">
        <div class="galleryItem">
            <h1 class="galleryTitle">Be Yourself!</h1>
            <img decoding="async" src="https://images.pexels.com/photos/13159244/pexels-photo-13159244.jpeg"
                alt="" class="galleryImg">
        </div>
        <div class="galleryItem">
            <img decoding="async" src="https://images.pexels.com/photos/2982100/pexels-photo-2982100.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
                alt="" class="galleryImg">
            <h1 class="galleryTitle">This is the First Day of Your New Life</h1>
        </div>
        <div class="galleryItem">
            <h1 class="galleryTitle">Just Do it!</h1>
            <img decoding="async" src="https://images.pexels.com/photos/1018911/pexels-photo-1018911.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
                alt="" class="galleryImg">
        </div>
    </div>
    <div class="newSeason">
        <div class="nsItem">
            <img decoding="async" src="https://images.pexels.com/photos/34514/spot-runs-start-la.jpg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
                alt="" class="nsImg">
        </div>
        <div class="nsItem">
            <h3 class="nsTitleSm">WINTER NEW ARRIVALS</h3>
            <h1 class="nsTitle">New Season</h1>
            <h1 class="nsTitle">New Collection</h1>
            <a href="#nav">
                <button class="nsButton">CHOOSE YOUR STYLE</button>
            </a>
        </div>
        <div class="nsItem">
            <img decoding="async" src="https://images.pexels.com/photos/7856965/pexels-photo-7856965.jpeg?auto=compress&cs=tinysrgb&dpr=2&w=500"
                alt="" class="nsImg">
        </div>
    </div>
    <footer>
        <div class="footerLeft">
            <div class="footerMenu">
                <h1 class="fMenuTitle">About Us</h1>
                <ul class="fList">
                    <li class="fListItem">Company</li>
                    <li class="fListItem">Contact</li>
                    <li class="fListItem">Careers</li>
                    <li class="fListItem">Affiliates</li>
                    <li class="fListItem">Stores</li>
                </ul>
            </div>
            <div class="footerMenu">
                <h1 class="fMenuTitle">Useful Links</h1>
                <ul class="fList">
                    <li class="fListItem">Support</li>
                    <li class="fListItem">Refund</li>
                    <li class="fListItem">FAQ</li>
                    <li class="fListItem">Feedback</li>
                    <li class="fListItem">Stories</li>
                </ul>
            </div>
            <div class="footerMenu">
                <h1 class="fMenuTitle">Products</h1>
                <ul class="fList">
                    <li class="fListItem">Air Force</li>
                    <li class="fListItem">Air Jordan</li>
                    <li class="fListItem">Blazer</li>
                    <li class="fListItem">Crater</li>
                    <li class="fListItem">Hippie</li>
                </ul>
            </div>
        </div>
        <div class="footerRight">
            <div class="footerRightMenu">
                <h1 class="fMenuTitle">Subscribe to our newsletter</h1>
                <div class="fMail">
                    <input type="text" placeholder="your@email.com" class="fInput">
                    <button class="fButton">Join!</button>
                </div>
            </div>
            <div class="footerRightMenu">
                <h1 class="fMenuTitle">Follow Us</h1>
                <div class="fIcons">
                    <img decoding="async" src="./img/facebook.png" alt="" class="fIcon">
                    <img decoding="async" src="./img/twitter.png" alt="" class="fIcon">
                    <img decoding="async" src="./img/instagram.png" alt="" class="fIcon">
                    <img decoding="async" src="./img/whatsapp.png" alt="" class="fIcon">
                </div>
            </div>
            <div class="footerRightMenu">
                <span class="copyright">@John Doe. All rights reserved. 2022.</span>
            </div>
        </div>
    </footer>
    <script src="./app.js"></script>
</body>

</html>
style.css
html {
  scroll-behavior: smooth;
  font-family: 'League Spartan', sans-serif;
font-family: 'Nunito', sans-serif;
font-family: 'Palanquin Dark', sans-serif;
font-family: 'Roboto Slab', serif;

}

body {
  font-family: "Lato", sans-serif;
  padding: 0;
  margin: 0;
}

nav {
  /* background-color: #111; */
  background-color: #232c5b;
  color: white;
  padding: 20px 50px;
}

.navTop {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.search {
  display: flex;
  align-items: center;
  background-color: gray;
  padding: 10px 20px;
  border-radius: 10px;
}

.searchInput {
  border: none;
  background-color: transparent;
}

.searchInput::placeholder {
  color: lightgray;
}

.limitedOffer {
  font-size: 20px;
  border-bottom: 2px solid rgb(194, 40, 156);
  cursor: pointer;
}

.navBottom {
  display: flex;
  align-items: center;
  justify-content: center;
}

.menuItem {
  margin-right: 50px;
  cursor: pointer;
  color: lightgray;
  font-weight: 400;
}

.slider {
  background: url(https://images.pexels.com/photos/7078622/pexels-photo-7078622.jpeg?auto=compress&cs=tinysrgb&w=600);
  /* background: url("https://images.unsplash.com/photo-1604147495798-57beb5d6af73?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2370&q=80"); */
  clip-path: polygon(0 0, 100% 0, 100% 100%, 0 85%);
  overflow: hidden;
}

.sliderWrapper {
  display: flex;
  width: 500vw;
  transition: all 1.5s ease-in-out;
}


.sliderItem {
  width: 100vw;
  display: flex;
  align-items: center;
  justify-content: center;
  position: relative;
}

.sliderBg {
  width: 750px;
  height: 750px;
  border-radius: 50%;
  position: absolute;
}

.sliderImg {
  z-index: 1;
}
#firsts{
  width: 60rem;
}
#jordan{
  width:50rem;
  transform: rotate(20deg);
}
#thirds{
  width: 50rem;
  transform: rotate(20deg);
  /* filter: invert(100%); */
}
#crater{
  width: 50rem;
}

.sliderTitle {
  position: absolute;
  top: 10%;
  right: 10%;
  font-size: 60px;
  font-weight: 900;
  text-align: center;
  color: rgb(44, 182, 32);
  z-index: 1;
}

.sliderPrice {
  position: absolute;
  top: 10%;
  left: 10%;
  font-size: 60px;
  font-weight: 300;
  text-align: center;
  color: white;
  border: 1px solid gray;
  z-index: 1;
}

.buyButton {
  position: absolute;
  top: 50%;
  right: 10%;
  font-size: 30px;
  font-weight: 900;
  color: white;
  border: 1px solid gray;
  background-color: black;
  z-index: 1;
  cursor: pointer;
}

.buyButton:hover {
  background-color: white;
  color: black;
}

.sliderItem:nth-child(1) .sliderBg {
  background-color: #e283ce;
}
.sliderItem:nth-child(2) .sliderBg {
  background-color: rebeccapurple;
}
.sliderItem:nth-child(3) .sliderBg {
  background-color: teal;
}
.sliderItem:nth-child(4) .sliderBg {
  background-color: cornflowerblue;
}
.sliderItem:nth-child(5) .sliderBg {
  background-color: rgb(124, 115, 80);
}

.sliderItem:nth-child(1) .sliderPrice {
  color: #369e62;
}
.sliderItem:nth-child(2) .sliderPrice {
  color: white;
}
.sliderItem:nth-child(3) .sliderPrice {
  color: teal;
}
.sliderItem:nth-child(4) .sliderPrice {
  color: cornflowerblue;
}
.sliderItem:nth-child(5) .sliderPrice {
  color: cornsilk;
}

.features {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 50px;
}

.feature {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
}

.featureIcon {
  width: 50px;
  height: 50px;
}

.featureTitle {
  font-size: 20px;
  font-weight: 600;
  margin: 20px;
}

.featureDesc {
  color: gray;
  width: 50%;
  height: 100px;
}

.product {
  height: 100vh;
  background-color: rgb(107, 101, 101);
  position: relative;
  clip-path: polygon(0 15%, 100% 0, 100% 100%, 0% 100%);
}

.payment {
  width: 500px;
  height: 500px;
  background-color: white;
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  margin: auto;
  padding: 10px 50px;
  display: none;
  flex-direction: column;
  -webkit-box-shadow: 0px 0px 13px 2px rgba(0, 0, 0, 0.3);
  box-shadow: 0px 0px 13px 2px rgba(0, 0, 0, 0.3);
}

.payTitle {
  font-size: 20px;
  color: lightgray;
}

label {
  font-size: 14px;
  font-weight: 300;
}

.payInput {
  padding: 10px;
  margin: 10px 0px;
  border: none;
  border-bottom: 1px solid gray;
}

.payInput::placeholder {
  color: rgb(163, 163, 163);
}

.cardIcons {
  display: flex;
}

.cardIcon {
  margin-right: 10px;
}

.cardInfo {
  display: flex;
  justify-content: space-between;
}

.sm {
  width: 30%;
}

.payButton {
  position: absolute;
  height: 40px;
  bottom: -40;
  width: 100%;
  left: 0;
  -webkit-box-shadow: 0px 0px 13px 2px rgba(0, 0, 0, 0.3);
  box-shadow: 0px 0px 13px 2px rgba(0, 0, 0, 0.3);
  background-color: #369e62;
  color: white;
  border: none;
  cursor: pointer;
}

.close {
  width: 20px;
  height: 20px;
  position: absolute;
  background-color: gray;
  color: white;
  top: 10px;
  right: 10px;
  display: flex;
  align-items: center;
  justify-content: center;
  cursor: pointer;
  padding: 2px;
}

.productImg {
  width: 50%;
  margin-top: 6rem;
}

.productDetails {
  position: absolute;
  top: 10%;
  right: 0;
  width: 40%;
  padding: 50px;
}

.productTitle {
  font-size: 75px;
  font-weight: 900;
}

.productDesc {
  font-style: 24px;
  color: rgb(241, 234, 234);
}

.colors,
.sizes {
  display: flex;
  margin-bottom: 20px;
}

.color {
  width: 32px;
  height: 32px;
  border-radius: 5px;
  background-color: rgb(255, 247, 247);
  margin-right: 10px;
  cursor: pointer;
}

.color:last-child {
  background-color: darkblue;
}

.size {
  padding: 5px 20px;
  border: 1px solid black;
  margin-right: 10px;
  cursor: pointer;
  font-size: 20px;
}

.productButton {
  float: right;
  padding: 10px 20px;
  background-color: black;
  color: white;
  font-weight: 600;
  cursor: pointer;
}

.productButton:hover {
  background-color: white;
  color: black;
}

.gallery {
  padding: 50px;
  display: flex;
}

.galleryItem {
  flex: 1;
  padding: 50px;
}

.galleryImg {
  width: 100%;
}

.newSeason {
  display: flex;
}

.nsItem {
  flex: 1;
  background-color: black;
  color: white;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-align: center;
}

.nsImg {
  width: 100%;
  height: 500px;
}

.nsTitle {
  font-size: 40px;
}

.nsButton {
  padding: 15px;
  font-weight: 600;
  cursor: pointer;
}

footer {
  display: flex;
}

.footerLeft {
  flex: 2;
  display: flex;
  justify-content: space-between;
  padding: 50px;
}

.fMenuTitle {
  font-size: 16px;
}

.fList {
  padding: 0;
  list-style: none;
}

.fListItem {
  margin-bottom: 10px;
  color: gray;
  cursor: pointer;
}

.footerRight {
  flex: 1;
  padding: 50px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}

.fInput {
  padding: 5px;
}

.fButton {
  padding: 5px;
  background-color: black;
  color: white;
}

.fIcons{
  display: flex;
}

.fIcon{
  width: 20px;
  height: 20px;
  margin-right: 10px;
}

.copyright{
  font-weight: 300;
  font-size: 14px;
}

@media screen and (max-width:480px) {
  nav{
    padding: 20px;
  }

  .search{
    display: none;
  }

  .navBottom{
    flex-wrap: wrap;
  }

  .menuItem{
    margin: 20px;
    font-weight: 700;
    font-size: 20px;
  }

  .slider{
    clip-path: none;
  }

  .sliderImg{
    width: 90%;
  }

  .sliderBg{
    width: 100%;
    height: 100%;
  }

  .sliderTitle{
    display: none;
  }

  .sliderPrice{
    top: unset;
    bottom: -50;
    left: 0;
    background-color: lightgrey;
  }

  .buyButton{
    right: 0;
    top: 0;
  }

  .features{
    flex-direction: column;
  }

  .product{
    clip-path: none ;
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .productImg{
    width: 80%;
  }

  .productDetails{
    width: 100%;
    padding: 0;
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    position: relative;
    top: 0;
  }

  .productTitle{
    font-size: 50px;
    margin: 0;
  }

  .gallery{
    display: none;
  }

  .newSeason{
    flex-direction: column;
  }

  .nsItem:nth-child(2){
    padding: 50px;
  }
  footer{
    flex-direction: column;
    align-items: center;
  }

  .footerLeft{
    padding: 20px;
    width: 90%;
  }

  .footerRight{
    padding: 20px;
    width: 90%;
    align-items: center;
    background-color: whitesmoke;
  }

  .payment{
    width: 90%;
    padding: 20px;
  }
}
app.js
const wrapper = document.querySelector(".sliderWrapper");
const menuItems = document.querySelectorAll(".menuItem");

const products = [
  {
    id: 1,
    title: "Air Force",
    price: 119,
    colors: [
      {
        code: "black",
        img: "./img/air.png",
      },
      {
        code: "darkblue",
        img: "./img/air2.png",
      },
    ],
  },
  {
    id: 2,
    title: "Air Jordan",
    price: 149,
    colors: [
      {
        code: "lightgray",
        img: "./img/jordan.png",
      },
      {
        code: "green",
        img: "./img/jordan2.png",
      },
    ],
  },
  {
    id: 3,
    title: "Blazer",
    price: 109,
    colors: [
      {
        code: "lightgray",
        img: "./img/blazer.png",
      },
      {
        code: "green",
        img: "./img/blazer2.png",
      },
    ],
  },
  {
    id: 4,
    title: "Crater",
    price: 129,
    colors: [
      {
        code: "black",
        img: "./img/crater.png",
      },
      // {
      //   code: "lightgray",
      //   img: "./img/crater2.png",

      // },
    ],
  },
  {
    id: 5,
    title: "Hippie",
    price: 99,
    colors: [
      {
        code: "gray",
        img: "./img/hippie.png",
      },
      {
        code: "black",
        img: "./img/hippie2.png",
      },
    ],
  },
];

let choosenProduct = products[0];

const currentProductImg = document.querySelector(".productImg");
const currentProductTitle = document.querySelector(".productTitle");
const currentProductPrice = document.querySelector(".productPrice");
const currentProductColors = document.querySelectorAll(".color");
const currentProductSizes = document.querySelectorAll(".size");

menuItems.forEach((item, index) => {
  item.addEventListener("click", () => {
    //change the current slide
    wrapper.style.transform = `translateX(${-100 * index}vw)`;

    //change the choosen product
    choosenProduct = products[index];

    //change texts of currentProduct
    currentProductTitle.textContent = choosenProduct.title;
    currentProductPrice.textContent = "$" + choosenProduct.price;
    currentProductImg.src = choosenProduct.colors[0].img;

    //assing new colors
    currentProductColors.forEach((color, index) => {
      color.style.backgroundColor = choosenProduct.colors[index].code;
    });
  });
});

currentProductColors.forEach((color, index) => {
  color.addEventListener("click", () => {
    currentProductImg.src = choosenProduct.colors[index].img;
  });
});

currentProductSizes.forEach((size, index) => {
  size.addEventListener("click", () => {
    currentProductSizes.forEach((size) => {
      size.style.backgroundColor = "white";
      size.style.color = "black";
    });
    size.style.backgroundColor = "black";
    size.style.color = "white";
  });
});

const productButton = document.querySelector(".productButton");
const payment = document.querySelector(".payment");
const close = document.querySelector(".close");

productButton.addEventListener("click", () => {
  payment.style.display = "flex";
});

close.addEventListener("click", () => {
  payment.style.display = "none";
});
```
# Lab: 07 - Programming with JavaScript

**First let's have a quick brief about website**

*A site is a restaurant that offers a specific type of order in partnership with other webites that offer diffrent order* `Food Time ` and `Food Hut`


> To Develop the website we have add a script that take a info from customer like name and address and we use  : 
* Promot function 
* If Statment
* Validation  

## Let's Start and see a Part Of Code 

> Page Redirection

*It will Redirection the customer according to his order input*
*so if user enter order number* `1` *It will Redirection To Food Time and if enter* `3` *It will Redirection To Food HUT site Else it will be in the site*
```
if (order==1){

    pagelink='https://joudi12.github.io/lab04/';
    pagename='Food Time';

   } else if (order==3){
    pagelink=' https://randalsallaq.github.io/restaurant-04/';
    pagename='Hut Food';
   }
   else {

    pagelink='https://aghyadalbalkhi-asac.github.io/Lab-04---Structure-web-pages-with-HTML/';
    pagename='Damsucs Food';
   }


```

> Validation
*It To Check If user Enter a correct Value or Not*
*Like a user Name , It check if the value is null* `NoThing` *or* `Empty`

```
 if (order!==1 || order!==3){
      alert("order Must be a Number");  
      order = prompt("Please Enter Number of Order");}
      
      --------------------------------------------------------------------------------------
      
      //Name Validtion 
if (customerName==null || customerName==""){
   alert("Name can't be blank");  
   customerName = prompt("Please Enter Your Name");
}

```
## Contact Info : 
**Please Feel Free To Contact Me When You Need help ^_^**
* [www.facebook.com/aghyadalbalkhi](www.facebook.com/aghyadalbalkhi)
* Email : aghyadalbalkhi@gmail.com


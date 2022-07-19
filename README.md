### Project:
* **KM-Homes** - Aim of this application is to connect serve Sellers, Buyers, Realtors in most efficient manner.
---
### Project Description:
* Aim of this application is to connect serve Sellers, Buyers, Realtors in most efficient manner.
---
### Structure & Design Principle:    
<img src='read_me_images/design_principle.jpg'/>

---
### Frameworks & Applications used:
* Django, Bootstrap, HTML, CSS, JS, Heroku, Postgresql
---
### Featured Pages:
* **Register** 
* **Login**
* **Home** 
* **Properties** 
* **About Us** 
* **Contact Us**
* **Dashboard**
* **Profile** 
* **Logout** 
---
### Register page:
* Helps User to Create his/her account.
    <img src='read_me_images/registration/reg1.png'/>
    <br>
  
* If User gave valid parameters then it will do Registration Successful & it will navigate User to Login page.
    <img src='read_me_images/registration/reg2.png'/>

    <img src='read_me_images/registration/reg3.png'/>
    <br>

* Else, User will get validation errors based on the parameters.
    <img src='read_me_images/registration/reg_v.png'/>
    <br>
---
### Login page:
* Helps User to login his/her account.
    <img src='read_me_images/login/login1.png'/>
    <br>

* If User gave valid credentials, then it will Login Successfully & navigate User to Dashboard page.
    <img src='read_me_images/login/login2.png'/>

    <img src='read_me_images/login/login3.png'/>
    <br>

* Else, User will get validation errors based on the parameters.
    <img src='read_me_images/login/login_v.png'/>
---
### Home page:
* Consists of Search feature & Latest Property details.
    <img src='read_me_images/home/1.png'/>
    <br>

* Search form helps User to search Properties based on his/her expectation.
    <img src='read_me_images/home/2.png'/>

    <img src='read_me_images/home/3.png'/>
    <br>

* If none of the search criteria is mentioned by User, then Search form will shows all the Properties listed in our website.
    <img src='read_me_images/home/4.png'/>

    <img src='read_me_images/home/5.png'/>
---
### Properties page:
* Shows complete list of properties for sale.
    <img src='read_me_images/properties/1.png'/>
    <br>

* User can view details of a property by clicking **"More info"**.
    <img src='read_me_images/properties/2.png'/>
    <br>

* If User is interested in property, then he/she can raise Inquiry by clicking **"Make an Inquiry"**.
    <img src='read_me_images/properties/3.png'/>
    <br>

* If User made successful inquiry then he/she will recieve Confirmation mail from **KM-Home team**.
    <img src='read_me_images/properties/5.png'/>
    <img src='read_me_images/properties/6.png'/>
    <br>

* Similarly, realtor for that property also get notification mail from **KM-Home team**.
    <img src='read_me_images/properties/7.png'/>
    <img src='read_me_images/properties/8.png'/>
    <br>

* If User made successful inquiry then he/she will get Success message notification.
    <img src='read_me_images/properties/success.png'/>
    <br>

* Also inquired property will get added to Dashboard page.
    <img src='read_me_images/properties/9.png'/>
    <br>

* Users are allowed to raise one inquiry for single property.
* If User tries to raise multiple inquiries for single property then he/she will get Error message notification.
    <img src='read_me_images/properties/fail.png'/>
---
### About Us page:
* Shows Company policies & Team details.
    <img src='read_me_images/basic_pages/about.png'/>
---
### Contact Us page:
* It helps Sellers to communicate with KM-Homes Teams.
    <img src='read_me_images/contact_us/1.png'/>
    <img src='read_me_images/contact_us/2.png'/>
    <br>

* Requester will get notification mail from KM-Homes Teams. 
    <img src='read_me_images/contact_us/3.jpg'/>
    <img src='read_me_images/contact_us/4.png'/>
    <br>

* If request is raised successfully, he/she will get redirected to home page.
    <img src='read_me_images/contact_us/5.png'/>
    <br>

* Else, Requester will get validation errors based on the parameters.
    <img src='read_me_images/contact_us/fail.png'/>
---
### Dashboard page:
* Helps to keep track of User's inquiry list.
    <img src='read_me_images/dashboard/1.png'/>
    <img src='read_me_images/dashboard/2.png'/>
---
### Profile page:
* Helps User to maintain his/her profile details. 
    <img src='read_me_images/profile/1.png'/>
    <br>

* If User provided valid parameters. Then profile details got updated & he/she will get success notification. 
    <img src='read_me_images/profile/2.png'/>
    <br>

* Else, User will get validation errors based on the parameters.
    <img src='read_me_images/profile/3.png'/>
---
### Logout page:
* Helps User to logout from his/her account & get navigated to Home page with success message.
    <img src='read_me_images/logout/1.png'/>
    <img src='read_me_images/logout/2.png'/>
---
## Extra Features:

* Password reset.
* Change password.
* Preventing Dashboard/Property/Profile pages from Unauthorized User access.
* Admin Panel for administration purpose.
---
### Password reset:
* click **"Forgot password?"** from login page.
    <img src='read_me_images/reset_pwd/1.png'/>
    <br>

* User should enter his/her registered email address.
    <img src='read_me_images/reset_pwd/2.png'/>
    <br>

* It will send **"Reset Password"** link to registered email address.
    <img src='read_me_images/reset_pwd/3.png'/>
    <img src='read_me_images/reset_pwd/4.png'/>
    <img src='read_me_images/reset_pwd/5.png'/>
    <br>

* It will redirect User to **"Password Reset"** page.
    <img src='read_me_images/reset_pwd/6.png'/>
    <br>

* Once password reset was done. Finally, User get success notification.
    <img src='read_me_images/reset_pwd/7.png'/>
---
### Change password:

* click **"Change Password"** from Profile page.
    <img src='read_me_images/change_pwd/1.png'/>
    <br>

* User should enter Old & New password.
    <img src='read_me_images/change_pwd/2.png'/>
    <br>

* Once password got changed. Finally, User will be redirected to **"Profile page"** with success notification.
    <img src='read_me_images/change_pwd/3.png'/>
---
### Preventing Dashboard/Property/Profile pages from Unauthorized User access:

* After logout, If user trying to access Dashboard/Property/Profile page. User will get redirected to **"Login Page"**. After successful login User will be redirected to expected page.
    <br>

* Similarly, above scenario will be applicable for Unauthorized user.

    * https://km-homes-djangoapp.herokuapp.com/accounts/dashboard/
    * https://km-homes-djangoapp.herokuapp.com/listings/7
    * https://km-homes-djangoapp.herokuapp.com/accounts/profile/
    <br>

* Below, I have mentioned only Unauthorized Profile page access scenario.
    <img src='read_me_images/unauth_protection/1.png'/>
    <img src='read_me_images/unauth_protection/2.png'/>
    <img src='read_me_images/unauth_protection/3.png'/>
---

### Admin Panel for administration purpose:

* Website admin panel.
    <img src='read_me_images/admin_panel/admin.png'/>
    <br>
* Administrator have complete access to add/remove Properties from Listings tab.
    <img src='read_me_images/admin_panel/listing.png'/>    
    <img src='read_me_images/admin_panel/listing2.png'/>
    <br>
* Administrator have complete access to add/remove Realtor from Realtors tab.
    <img src='read_me_images/admin_panel/realtor.png'/>    
    <img src='read_me_images/admin_panel/realtor2.png'/>
---

### Future Updates:

* User can able to **Signed Up** with Gmail or Facebook account.
* Planning to implement **Machine Learning** feature in Property search.
* Planning to implement **Data Analytics** feature to generate reports for Property sale.

---

### Conclusion:

* Thanks for reading this Document.

* I really appreciate your Patience & Effort.

* Kindly please share your valuable feedback & comments through ( +91-9585675562, productdeveloper.karthikeyan@gmail.com ).

* Connect with me at [LinkedIn](https://www.linkedin.com/in/karthikeyan-m-576336240/) & [Github](https://github.com/developer-karthikeyan).

---

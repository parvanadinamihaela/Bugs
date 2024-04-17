###Bugs sample###


Below are some bugs that I find during the previous QA course.

..................................................

**Descriptions:**

The price displayed for a specific product is incorrect in cart.


**Steps to reproduced:**

1-Go to STORE 

2-Add one or two products in cart 

**Expected result:**

After adding the product to the cart , the currency in witch the payment is made should also appear .

**Actual result**

The currency in witch the payment must be made does not appear.

.....................................................

**Descriptions:**

When accessing the product page on demonlaze.com from a mobile device, the image is not centered correctly and appears cropped.


**Steps to Reproduce:**

1-Open a mobile web browser.

2-Navigate to demonlaze.com.

3-Go to the product page.

4-Observe the alignment and cropping of the image.


**Expected results:**

The image should be centered and fully visible on the product page, regardless of the device being used.

**Actual results:**

The image is not centered correctly and appears cropped, cutting off parts of the image, when viewed from a mobile device.

..................................................

**Descriptions:**

When accessing demonlaze.com from a mobile device, the menu is not properly aligned and centered.


**Steps to reproduce:**

1-Open a mobile web browser.

2-Navigate to demonlaze.com.

3-Observe the alignment and centering of the mobile menu.


**Expected results:**

The mobile menu should be properly aligned and centered on the screen, ensuring easy access and readability for users.


**Actual results:**

The mobile menu is misaligned and not centered, impacting the user experience and making navigation difficult.

.........................................................

**Descriptions:**

A vulnerability has been identified in the ordering process on demonlaze.com, allowing users to make purchases by inputting certain characters, including credit card information, sequentially.

**Steps to Reproduce:**

1-Begin the ordering process on demonlaze.com.

2-Input specific characters, including credit card information, sequentially during the checkout process.

3-Complete the order successfully without providing valid payment information.

**Expected Results:**

Users should not be able to bypass the payment process by inputting arbitrary characters or invalid credit card information.

**Actual Results:**

Users are able to make purchases by inputting certain characters sequentially during the checkout process, including credit card information, without providing valid payment information.

............................................................

**Descriptions:**

On the About Us page of www.demoblaze.com, the play button is not centered properly.

**Steps to Reproduce:**

1-Visit www.demoblaze.com.

2-Navigate to the About Us page.

3-Locate the play button element on the page.

**Expected results:**

The button should be horizontally centered within its container, providing a visually appealing and balanced layout.

**Actual results:**

The button is not horizontally centered within its container, resulting in an unbalanced appearance and potential inconsistency in design.


...........................................................................

**Descriptions:**

The contact form on www.demoblaze.com allows users to send a message without providing an email address.


**Steps to Reproduce:**

1-Visit www.demoblaze.com.

2-Navigate to the contact page.

3-Fill out the contact form without providing an email address.

4-Submit the form.

**Expected results:**

The contact form should require users to provide a valid email address before allowing them to send a message.

**Actual results:**

Users are able to send messages through the contact form without entering an email address, which may lead to difficulties in responding to inquiries or contacting users.


............................................................................

**Descriptions:**

On STORE , users can make multiple purchases by repeatedly pressing the purchase button on the order access page.


**Steps to Reproduce:**

1-Visit STORE .

2-Navigate to the order access page.

3-Select a product and click on the purchase button.

4-Without refreshing the page, repeatedly press the purchase button multiple times.


**Expected result:**

Users should only be able to make a single purchase per click of the purchase button, preventing unintended multiple purchases.


**Actual result:**

Repeatedly pressing the purchase button allows users to make multiple purchases of the same product without refreshing the page, potentially leading to unintentional duplicate orders.


...........................................................


**Descriptions:**

After logging into their accounts on STORE , users do not have access to a password recovery field or mechanism.


**Steps to Reproduce:**

1-Log into your account on STORE  using your credentials.

2-Attempt to recover your password by accessing the password recovery feature or field.

3-Observe the absence of any password recovery option or field.


**Expected results:** 

After logging in, users should have access to a password recovery mechanism or field in case they forget their password.


**Actual results:**

Upon logging in, users do not find any password recovery option or field available, leaving them unable to recover their password if forgotten.

.............................................................


**Descriptions:**

In the bank application , any user can log in without proper authentication.

**Steps to reproduce:**

1-Access the bank application using the provided XYZ Bank 

2-Press the  “CUSTOMER LOGIN “ button 

3-Choose any name form the drop down list

4-Observe that the application allows access and logs in the user without proper authentication.

 

**Expected results:** 

The application should only allow access to valid users who provide correct authentication credentials (username and password).

**Actual results:**

The application allows access to any user, regardless of the provided credentials, thereby bypassing proper authentication.

..........................................................



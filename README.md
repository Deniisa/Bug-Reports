# Bug Report Samples

Below you can find some Bug Report samples that I wrote during my QA course.

-------------------------------------------

**VIDEOJS warning in Chrome console**

**Priority & severity**
P3 - Normal

**Description**
VIDEOJS: WARN: A plugin named "reloadSourceOnError" already exists. You may want to avoid re-registering plugins!

**Steps to reproduce**
1. Go to www.demoblaze.com
2. Access the console

**Expected result**
There shouldn't be any errors in the console.

**Actual result**
The video doesn't appear on the website and the warning is visible in the console.

**Test data**
Website tested: www.demoblaze.com

--------------------------------------------------------

**Error 404 Page**

**Priority & severity**
P6 - Low

**Description**
This website doesn't have a customed 404 Page.
This error message is displayed: Error: Not Found
The requested URL /cart was not found on this server.

**Steps to reproduce**
1. Go to www.demoblaze.com
2. Add some invalid data to the URL and press enter

**Expected result**
A customed 404 Page should open with information about the URL or other suggestions.

**Actual result**
A 404 Not Found error message is displayed on a blank page, with no other information.

**Test data**
Invalid data added to the URL: /cart

-----------------------------------------------------------

**The website is loading very slow**

**Priority & severity**
P3 - Critical

**Description**
When accessing the website, it takes a long time to display the pages and information.

**Steps to reproduce**
1. Go to www.primariatechirghiol.ro
2. Open the developer tools 
3. Check the loading time and the used resources space

**Expected result**
The website should load quickly and the loading time and used resources space should be in normal parameters. 

**Actual result**
Loading time is 18.94 seconds, the resources space is 4.1MB and the website is loading slowly.

----------------------------------------------------

**Broken link**

**Priority & severity**
P6 - Low

**Description**
The link http://www.pensiunea-mareaneagra.ro/ doesn't work. 

**Steps to reproduce**
1. Go to https://www.primariatechirghiol.ro/home/info-turism/cazare/
2. Access the link with the text Pensiunea Marea Neagra 

**Expected result**
A new page should open and display the website for Pensiunea Marea Neagra.

**Actual result**
The link doesn't work and it shows an error message.

**Test data**
www.brokenlinkcheck.com

-------------------------------------------------------------

**Fake information used for purchase**

**Priority & severity**
P1 - Critical

**Description**
Fake data was used to purchase products and the message 'Thank you for your purchase!' appears.

**Steps to reproduce**
1. Go to  https://www.demoblaze.com2. 
2. Choose a product or more and add them to cart
3. Go to cart 
4. Finalize the order using fake information

**Expected result**
The user shouldn't be able to purchase the items using fake information.

**Actual result**
A message informs the user that the purchase was successful.

**Test data**
Name: denisa
Card number: 123456
Year: 2007

---------------------------------------------------------

**Lang parameter is not working properly**

**Priority & severity**
P6 - Normal

**Description**
When using the lang parameter to change the language in romanian, it doesn't translate all the words. 

**Steps to reproduce**
1. Go to https://openweathermap.org/api
2. Create an account to get an API key
3. Access Current Weather Data api doc
4. Use the API call provided to test the lang parameter in Postman 
5. Give the lang parameter the value 'ro'

**Expected result**
All the API responses should be translated in romanian.

**Actual result**
Some values are not translated in romanian, example: clouds, stations.

**Test data**
User: denisapop93@gmail.com
API key: 50l3uC3t5r5bo1 

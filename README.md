# Projects
<h1>API Testing Project for Restful Booker</h1>

The scope of this project is to use all API knowledge gained throught the Software Testing course and apply them in practice, using a live application.

API under test: **Restful Booker**

API documentation for the API restful-booker: https://restful-booker.herokuapp.com/apidoc/index.html#api-Booking

Tools used: **Postman, Newman**

Collection link: https://github.com/Dianab05/API-Testing-Project/blob/main/restful-booker.postman_collection.json

<h2>Tests performed</h2>

<ol>
<h4><li>Verify that the API is up and running  </li> </h4> 
  
HTTP method for request: **GET** <br>
Request description: **A simple health check endpoint to confirm whether the API is up and running.** <br>
Test types / techniques used: **Sanity testing**<br>
Response status code: **201 Created** <br>

**Below you can find a picture of the API request from Postman:**
<br>

<img src="https://github.com/Dianab05/Projects/assets/166596469/a1acbad4-21b4-45d7-bd95-f5a6ce1d29a1" width="700" height="500">

**JavaScript Tests:**

<img src="https://github.com/Dianab05/Projects/assets/166596469/bb9c8397-233b-4fc1-814a-abf4531282d5" width="700" height="500">


<h4><li> Verify if all bookings ids are displayed </li> </h4> 

HTTP method for request: **GET** <br>
Request description: **Returns the ids of all the bookings that exist within the API. Can take optional query strings to search and return a subset of booking ids.** <br>
Test types / techniques used: **Functional testing**<br>
Response status code: **200 OK** <br>

**Below you can find a picture of the API request from Postman:** <br>

<img src="https://github.com/Dianab05/Projects/assets/166596469/e4973156-7407-40cc-953d-bd53dd6cdc1e" width="700" height="500">
<br>

**JavaScript Tests:**

<img src="https://github.com/Dianab05/Projects/assets/166596469/8edd2c66-40cc-4c40-8b4d-59b8715b9f1d" width="700" height="500">
<br>

<h4><li> Verify if bookings can be filtered by firstname/lastname </li> </h4> 

HTTP method for request: **GET** <br>
Request description: **Return bookings with a specific firstname/lastname** <br>
Test types / techniques used: **Functional testing**<br>
Response status code: **200 OK** <br>

**Below you can find a picture of the API request from Postman:** <br>
<img src="https://github.com/Dianab05/Projects/assets/166596469/2be00a93-0be8-450e-8ad7-81076ff7a05a" width="700" height="500">

**JavaScript Tests:**

<img src="https://github.com/Dianab05/Projects/assets/166596469/68bfc797-8440-41a2-950c-5f012865f482" width="700" height="500">

<h4><li> Verify if informations are displayed about one specific booking</li> </h4> 

HTTP method for request: **GET** <br>
Request description: **Returns a specific booking based upon the booking id provided** <br>
Test types / techniques used: **Functional testing**<br>
Response status code: **200 OK** <br>

**Below you can find a picture of the API request from Postman:** <br>
<img src="https://github.com/Dianab05/Projects/assets/166596469/f00f82f5-3532-4d68-b104-1d780ac2fc28" width="700" height="500">

**JavaScript Tests:**

<img src="https://github.com/Dianab05/Projects/assets/166596469/1b327515-b395-4704-96d4-0a58bcea187f" width="700" height="500">

<h4><li>Negative testing - Verify if informations cannot be displayed about an invalid booking</li> </h4> 

HTTP method for request: **GET** <br>
Request description: **An error is displayed when entered an invalid booking id** <br>
Test types / techniques used: **Negative testing**<br>
Response status code: **404 Not Found** <br>

**Below you can find a picture of the API request from Postman:** <br>

<img src="https://github.com/Dianab05/API-Testing-Project/assets/166596469/7b594c76-6d93-4969-ba88-d2ebf9369864" width="700" height="500">

**JavaScript Tests:**

<img src="https://github.com/Dianab05/API-Testing-Project/assets/166596469/41da0ab9-b5c6-48d7-bd11-f1e306ef73ef" width="700" height="500">


<h4><li>Verify if a new booking can be created</li> </h4> 

HTTP method for request: **POST** <br>
Request description: **Creates a new booking in the API** <br>
Test types / techniques used: **Functional testing**<br>
Response status code: **200 OK** <br>

**Below you can find a picture of the API request from Postman:** <br>

<img src="https://github.com/Dianab05/API-Testing-Project/assets/166596469/777cf521-3979-44a2-ac8c-8007a1a9b1ab" width="700" height="500">


**JavaScript Tests:**

<img src="https://github.com/Dianab05/API-Testing-Project/assets/166596469/1c1b0b65-2d39-473d-82c7-acd9a5eaaf4b" width="700" height="500">


<h4><li>Verify if a current booking can be updated</li> </h4> 

HTTP method for request: **PUT** <br>
Request description: **Updates a current booking** <br>
Test types / techniques used: **Functional testing**<br>
Response status code: **200 OK** <br>

**Below you can find a picture of the API request from Postman:** <br>

<img src="https://github.com/Dianab05/API-Testing-Project/assets/166596469/74b695c7-8334-4bee-9033-e28229038edd" width="700" height="500">


**JavaScript Tests:**

<img src="https://github.com/Dianab05/API-Testing-Project/assets/166596469/f8791919-0f12-452c-9aa5-697118e57ef4" width="700" height="500">

<h4><li>Negative testing- Verify if an invalid booking cannot be updated</li> </h4> 

HTTP method for request: **PUT** <br>
Request description: **An error message is displayed when try to update an invalid booking id** <br>
Test types / techniques used: **Negative testing**<br>
Response status code: **405 Method Not Allowed** <br>

**Below you can find a picture of the API request from Postman:** <br>

<img src="https://github.com/Dianab05/API-Testing-Project/assets/166596469/e87ca30e-d44b-42f2-9404-a0c0d2c56e47" width="700" height="500">

**JavaScript Tests:**

<img src="https://github.com/Dianab05/API-Testing-Project/assets/166596469/59d05f5a-4fad-4184-80dc-ff5cbaa7f594" width="700" height="500">


<h4><li>Verify if a current booking can be updated with partial payload</li> </h4> 

HTTP method for request: **PATCH** <br>
Request description: **Updates a current booking with a partial payload** <br>
Test types / techniques used: **Functional testing**<br>
Response status code: **200 OK** <br>

**Below you can find a picture of the API request from Postman:** <br>

<img src="https://github.com/Dianab05/API-Testing-Project/assets/166596469/24d31323-e564-4793-9822-39d9348b017d" width="700" height="500">

**JavaScript Tests:**

<img src="https://github.com/Dianab05/API-Testing-Project/assets/166596469/5f828b61-ec84-4020-9750-97c3ab450065" width="700" height="500">


<h4><li>Negative testing- Verify if a current booking cannot be updated without authentication</li> </h4> 

HTTP method for request: **PATCH** <br>
Request description: **An error message is displayed when try to update a booking without authentication** <br>
Test types / techniques used: **Negative testing**<br>
Response status code: **403 Forbidden** <br>

**Below you can find a picture of the API request from Postman:** <br>

<img src="https://github.com/Dianab05/API-Testing-Project/assets/166596469/166f693e-a6a0-4fdf-b01d-2bef1489d9cc" width="700" height="500">


**JavaScript Tests:**

<img src="https://github.com/Dianab05/API-Testing-Project/assets/166596469/ad4be6c1-cef8-40c7-b831-15f793754b55" width="700" height="500">


<h4><li>Verify if an existing booking can be deleted</li> </h4> 

HTTP method for request: **DELETE** <br>
Request description: **Delete a current booking from the API** <br>
Test types / techniques used: **Functional testing**<br>
Response status code: **201 Created** <br>

**Below you can find a picture of the API request from Postman:** <br>

<img src="https://github.com/Dianab05/API-Testing-Project/assets/166596469/e738995d-263c-481d-b387-a0288810bc92" width="700" height="500">

**JavaScript Tests:**

<img src="https://github.com/Dianab05/API-Testing-Project/assets/166596469/36416080-d03a-4a91-a251-efff6ce907ad" width="700" height="500">

<h4><li>Negative testing - Verify that DELETE action cannot be performed without a booking id</li> </h4> 

HTTP method for request: **DELETE** <br>
Request description: **An error message is displayed when try to perform a delete action without mention a booking id** <br>
Test types / techniques used: **Negative testing**<br>
Response status code: **404 Not Found** <br>

**Below you can find a picture of the API request from Postman:** <br>

<img src="https://github.com/Dianab05/API-Testing-Project/assets/166596469/81aa73cc-5f2b-4fb4-9dd4-ae9ba53bbb8e" width="700" height="500">


**JavaScript Tests:**

<img src="https://github.com/Dianab05/API-Testing-Project/assets/166596469/00c85abe-ed7a-420a-9639-aa36be3aa52d" width="700" height="500">



</ol>

<h2>Execution report for the created API collection </h2>

**Below you can find the execution report that was generated through the Postman collection runner** <br>

![collection runner](https://github.com/Dianab05/API-Testing-Project/assets/166596469/b6b0de02-c3da-4b7c-a366-c6fc47670f00)
<br>


*Link for Postam collection runner*<br>
https://github.com/Dianab05/API-Testing-Project/blob/main/restful-booker.postman_collection_runner.json
<br>


**The collection was also run through Newman directly from the terminal, and the results can be found below**<br>

![newman report ](https://github.com/Dianab05/API-Testing-Project/assets/166596469/60af523f-8178-45e6-8a2d-8d274dcdfe09)
<br>


**Below you can find the Newman execution report HTMLExtra** <br>

![newman sc](https://github.com/Dianab05/API-Testing-Project/assets/166596469/1b776e08-5ea6-441f-bed1-27e9dd823fe1)


*Link for Newman execution report* <br>
https://github.com/Dianab05/API-Testing-Project/blob/main/restful-booker-newman%20report.html
<br>

<h2>Defects found</h2>

The following issues were identified while running the postman tests:<br>

![newman bugs1](https://github.com/Dianab05/API-Testing-Project/assets/166596469/8cf1d85a-dd20-49ee-bf92-7e38e91f7fae)
![newman bugs 2](https://github.com/Dianab05/API-Testing-Project/assets/166596469/12c67afc-327a-44de-b5a1-81570c7a1790)
<br>


<h2>Conclusions from Test Execution</h2>

<h4>Tests Created and Executed</h4>

Total number of tests created: **111** <br>
Total number of tests executed: **111** <br>
Percentage of requirements covered: **Approximately 95%** <br>

![newman conclusion](https://github.com/Dianab05/API-Testing-Project/assets/166596469/c40e0acb-7f99-46bf-8fc1-438f4db3d8ae)
<br>

<h4>Requirements Coverage</h4> 

Covered requirements: **Most of the specified requirements in the project scope were rigorously tested.** <br>
Untested functionalities: **There are a few minor functionalities that were not tested due to time and resource constraints**<br>

<h4>Bugs and Impact on Launch</h4>

Identified bugs: **4 bugs were reported during testing** <br> 
**Medium bugs: 3**(can be fixed later, but should be documented and scheduled for the next development cycle)<br>
**Minor bugs: 1** (do not impact primary functionality, can be resolved in the future)<br>

<h4>Risks and Recommendations</h4>

**Identified risks:** <br>
Potential performance issues with a very high number of simultaneous users.<br>
Lack of complete testing for export functionalities and advanced filtering.<br>

**Recommendations for launch:** <br>

Planning a post-launch testing cycle to address medium and minor bugs.<br>
Closely monitoring system performance and usage in the first few weeks post-launch.<br>
Encouraging users to report any encountered issues so they can be quickly addressed.<br>

<h4>Lessons Learned</h4>

**Planning and resources:** <br>
It is crucial to allocate enough time and resources to test all functionalities, including secondary ones, to ensure complete coverage.<br>
Automation: Using test automation tools can significantly speed up the process and improve testing accuracy.<br>
Communication: Effective communication between development and testing teams can prevent many issues and ensure all requirements are understood and properly covered.<br>
Documentation: Keeping detailed and updated documentation of the tests performed, identified bugs, and implemented solutions is essential for future development cycles.<br>
These conclusions and recommendations will contribute to improving the development and testing process for future projects, ensuring a smoother launch and a better user experience.<br>


# Projects
<h1>API Testing Project for Restful Booker</h1>

The scope of this project is to use all  API knowledge gained throught the Software Testing course and apply them in practice, using a live application.

Application under test: **Restful Booker**

Tools used: **Postman, Newman**

Collection link: https://restful-booker.herokuapp.com/apidoc/index.html#api-Booking

<h2>Tests performed</h2>

<ol>
<h4><li>Verify that the API is up and running  </li> </h4> 
  
HTTP method for request: **GET** <br>
Request description: **A simple health check endpoint to confirm whether the API is up and running.** <br>
Test types / techniques used: **Sanity testing**<br>
Response status code: **201 Created** <br>

**Below you can find a picture of the API request from Postman:**
<br>

![request 1](https://github.com/Dianab05/Projects/assets/166596469/a1acbad4-21b4-45d7-bd95-f5a6ce1d29a1)

**JavaScript Tests:**

![request 1 tests](https://github.com/Dianab05/Projects/assets/166596469/bb9c8397-233b-4fc1-814a-abf4531282d5)


<h4><li> Verify if all bookings ids are displayed </li> </h4> 

HTTP method for request: **GET** <br>
Request description: **Returns the ids of all the bookings that exist within the API. Can take optional query strings to search and return a subset of booking ids.** <br>
Test types / techniques used: **Functional testing**<br>
Response status code: **200 OK** <br>

**Below you can find a picture of the API request from Postman:** <br>

![request 2](https://github.com/Dianab05/Projects/assets/166596469/e4973156-7407-40cc-953d-bd53dd6cdc1e)
<br>

**JavaScript Tests:**
![request 2 tests](https://github.com/Dianab05/Projects/assets/166596469/8edd2c66-40cc-4c40-8b4d-59b8715b9f1d)
<br>

<h4><li> Verify if bookings can be filtered by firstname/lastname </li> </h4> 

HTTP method for request: **GET** <br>
Request description: **Return bookings with a specific firstname/lastname** <br>
Test types / techniques used: **Functional testing**<br>
Response status code: **200 OK** <br>

**Below you can find a picture of the API request from Postman:** <br>
![request 3 ](https://github.com/Dianab05/Projects/assets/166596469/2be00a93-0be8-450e-8ad7-81076ff7a05a)

**JavaScript Tests:**
![request 3 tests](https://github.com/Dianab05/Projects/assets/166596469/68bfc797-8440-41a2-950c-5f012865f482)

<h4><li> Verify if informations are displayed about one specific booking</li> </h4> 

HTTP method for request: **GET** <br>
Request description: **Returns a specific booking based upon the booking id provided** <br>
Test types / techniques used: **Functional testing**<br>
Response status code: **200 OK** <br>

**Below you can find a picture of the API request from Postman:** <br>
![request 4](https://github.com/Dianab05/Projects/assets/166596469/f00f82f5-3532-4d68-b104-1d780ac2fc28)

**JavaScript Tests:**

![request 4 tests](https://github.com/Dianab05/Projects/assets/166596469/1b327515-b395-4704-96d4-0a58bcea187f)



.............

<li>**Nume Request n**</li>

HTTP method for request: **Inserati aici metoda HTTP a requestului**<br>
Request description: **Inserati o scurta descriere a requestului, conform documentatiei de API**<br>
Test types / techniques used: **Inserati tipurile si tehnicile de testare folosite pentru acest request**<br>
Response status code: **Inserati aici status code-ul pe care l-ati obtinut in urma executiei requestului**<br>

Below you can find a picture of the API request from Postman:<br>

**Inserati aici o poza cu requestul din postman in care sa se observe request method, endpoint, request body si response body**<br>

JavaScript Tests:

**Inserati aici o poza cu testele in java script pe care le-ati definit impreuna cu rezultatele executiei acestora**<br>

</ol>

<h2>Execution report for the created API collection </h2>

Below you can find the execution report that was generated through the Postman collection runner. <br>

**Inserati aici o poza cu raportul de executie din Postman**<br>

The collection was also run through newman directly from the terminal, and the results can be found below:<br>

**Inserati aici o poza cu raportul de executie din Newman**<br>

<h2>Defects found</h2>

The following issues were identified while running the postman tests:<br>

****Inserati aici fie un fisier pdf care sa contina raportarea tuturor bug-urilor, fie le descrieti direct in git
Bug-urile trebuie sa contina titlu, preconditii, pasi de executie, rezultate asteptate si rezultate actuale.
Optional, bug-urile pot fi raportate in jira, si apoi puteti pune poze direct din jira**

<h2>Conclusions</h2>

**Inserati aici concluziile pe care le-ati obtinut in urma executarii testelor  si introduceti informatii cum ar fi cate teste au fost create si executate, ce procentaj aproximativ din cerintele in scop au fost acoperite, daca exista vreo functionalitate pe care nu ai apucat sa o testezi, daca bug-urile gasite impacteaza lansarea produsului in productie sau se pot fixa si ulterior, daca ai identificat riscuri de produs care trebuie mitigate, daca e vreo reecomandare pe care vrei sa o faci pentru lansare, daca sunt ceva lessons learned de care trebuie sa se tina cont la proiectele viitoare etc**


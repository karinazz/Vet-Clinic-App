# Web Application for Veterinary Clinic
The aim of the project was to identify the needs of a veterinary clinic and develop an application that would address these needs. After analyzing and identifying the domain, assumptions for the application were prepared, followed by the implementation phase. The application was developed using the Python programming language and the Django framework. <br> <br>
Technologies Used in the Project:
<div align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="40" alt="python logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/django/django-plain.svg" height="40" alt="django logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg" height="40" alt="bootstrap logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="40" alt="html5 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="40" alt="css3 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40" alt="javascript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" height="40" alt="postgresql logo"  />
<br><br>
CKEditor5 6.4.1, Bootstrap CDN Icons, Pillow 9.1.1, Gimp 2.10.30, RandomUserGeneratorAPI and others..

  <h2></h2>
<div align="left">
The most important functional requirements of the application:
<ul>
<li>Online appointment scheduling</li>
<li>Actors: logged-in user, logged-out user (receptionist or veterinarian), and administrator. <br>
1. A logged-in user, depending on the assigned group, has different permissions; for example, a receptionist manages appointments, while a veterinarian updates the patient's record.<br>
2. The administrator is a super user and can always use all created and available functions without the need for manual addition.<br>
3. An unauthenticated user, referred to as the Customer as the only user type without an account, will always remain logged out and will not have access to the employee panel (under the "Manage" tab). The Customer will only have access to browse all publicly available content on the website. The Customer will be able to create a reservation for an appointment by filling out the reservation form on the website, providing their personal information, the animal's details, and contact number.
<li>The navigation bar consists of 6 tabs: Home, About Us, Services, Schedule, Manage. The last tab, Manage, is only accessible to authorized individuals.</li>
<li>Managing the animal database.</li>
<li>Maintaining the list of appointments.</li>
<li>Blog management by authorized individuals.</li>
<li>Employee working hours.</li>
<li>List of employees.</li>
</ul>
</div>

 <h2></h2>

 # Frontend
 ## Homepage
 ![image](https://github.com/karinazz/vetapp/assets/48722433/99010aab-0e25-418c-a4a4-0d304f38367e)
 ![image](https://github.com/karinazz/vetapp/assets/48722433/3cb03047-53d4-4916-ab34-25ab4e137076)
 ![image](https://github.com/karinazz/vetapp/assets/48722433/270f96d7-d8e4-46b8-bb1f-b5520f924983)
 ![image](https://github.com/karinazz/vetapp/assets/48722433/c892b30e-7d96-4c33-b74b-6ba8da143ac8)
 ![image](https://github.com/karinazz/vetapp/assets/48722433/4c929ba2-25e5-42bc-9d88-a104f3d3eef0)
 ![image](https://github.com/karinazz/vetapp/assets/48722433/d1b3a3a3-ec96-4cb7-93db-09f0581834af)
![image](https://github.com/karinazz/vetapp/assets/48722433/2c442a63-5fad-4826-9353-7953649443c6)
## Employees
![image](https://github.com/karinazz/vetapp/assets/48722433/71323347-5804-469b-8159-3e57a2b0de13)
## Services
![image](https://github.com/karinazz/vetapp/assets/48722433/e8528d5c-4289-4a98-80c3-d948fc4c07a2)
## Rota
![image](https://github.com/karinazz/vetapp/assets/48722433/0d5ff306-a925-43a7-a43a-f8514bea37ca)
## Animal database f.e the dog named Kai
![image](https://github.com/karinazz/vetapp/assets/48722433/a48f4d04-d59a-4654-bb70-230d47bcc234)
## Form "choose a vet"
![image](https://github.com/karinazz/vetapp/assets/48722433/b6ceb56c-37d6-498e-b469-b8461fc97f16)
## Form "book an appointment"
![image](https://github.com/karinazz/vetapp/assets/48722433/9a3c8831-226d-45ee-9a17-d6e25fd0e4bf)
## Adding a new post
![image](https://github.com/karinazz/vetapp/assets/48722433/eca34b85-baee-4372-ade4-dffef4990cc8)


# Backend
## Models
### Reservation
![image](https://github.com/karinazz/vetapp/assets/48722433/1645eff9-7980-402c-8bcc-fa48fbf5a86c)

### Post
![image](https://github.com/karinazz/vetapp/assets/48722433/a75ab492-fc2e-49d9-8d3c-408d136a37e6)

### Working time
![image](https://github.com/karinazz/vetapp/assets/48722433/11574be3-28be-4d8f-8ab3-dc6d9960b5f6)

### Agenda
![image](https://github.com/karinazz/vetapp/assets/48722433/4bead4cf-499c-4140-a1cc-911f756eb632)

### Vet
![image](https://github.com/karinazz/vetapp/assets/48722433/6ae9460a-c8d2-43c2-8832-64ee5583f057)

### Animal
![image](https://github.com/karinazz/vetapp/assets/48722433/655a47bc-7b10-420d-a026-73a5bf1e29f0)


## Views 
![image](https://github.com/karinazz/vetapp/assets/48722433/7897840a-7ce5-445d-99c0-3272f37e4aaf)
![image](https://github.com/karinazz/vetapp/assets/48722433/7b6f5ed5-460e-4fd3-9c39-4ecf9d437710)


## Django ORM
![image](https://github.com/karinazz/vetapp/assets/48722433/c53a9c16-8909-40f6-a856-5c0583403eb9)
![image](https://github.com/karinazz/vetapp/assets/48722433/b17980bb-2f55-40eb-9f9e-e8ea61178e62)

  
## Forms
f.e Reservation form
![image](https://github.com/karinazz/vetapp/assets/48722433/334c46d6-041c-4412-a43f-f58cd169bd3b)


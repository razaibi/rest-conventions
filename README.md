# rest-conventions
Guidelines and best practices for naming API endpoints.


REST API Naming Conventions example : Employee Model


Intent : To get form to create a new employee
---
Url : GET 'employee/new'

Controller Function Name: new


Intent : Submit form to create an employee
---
Url : **POST** '/employee'

Controller Function Name: create

Intent : Get list of all employees
---
Url : **GET** '/employee'

Controller Function Name: index

Intent : Delete an employee  with *id*
---
Url : **DELETE** 'employee/*id*'

Controller Function Name: delete

Intent : Get form to update an existing employee
---
Url : **GET** 'employee/*id*/edit'
  
Controller Function Name: edit

Intent : Submit form to update an existing employee with *id*
---
Url : **PUT** '/employee/*id*'
  
Controller Function Name: update

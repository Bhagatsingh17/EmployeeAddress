# Employee_Address Project

## Frameworks and Language used:
 - Spring
 - Spring boot
 - My-Sql
 - Java

 ## Data Flow
 #### Controller
 ---Employee----
 - getEmployee
 - getEmployeeById
 - addEmployee
 - updateEmployee
 - deleteEmployee
 
 ---Address----
 - getALlAddress
 - addAllAddress
 - updateAddressData
 - deleteAddress

 #### Service
 ---Employee----
 - getAllEmployeeData
 - getEmployeeDataById
 - addEmployeeData
 - updateEmployeeData
 - deleteEmployeeData

 ---Address----
 - getAllAddressData
 - addAllAddressData
 - updateAddressData
 - deleteAddressData

 
 #### Repository
 ---Employee----

 IEmployeeRepository

 ---Address----

 IAddressRepository


 IEventRepository
 #### Model
 ---Employee----
 - employeeId
 - firstName
 - lastName
 - address
 
 ---Address----
 - addressId
 - street
 - city
 - state
 - zipcode
 
 
### Project Summary
Created a simple EMployee Address One to One relationship mapping java application to establish ont to one data relationship between these two models. Also performed CRUD operations on these data.

### How to use in your system?
 - Just Simply clone this reposit
 - Start your server
 - Perform operations 

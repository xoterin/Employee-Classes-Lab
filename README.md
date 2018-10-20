# Employee-Classes-Lab
// For the 14.5 lab

The classes in this lab describe a superclass named EmployeePerson and two derived classes, EmployeeManager and EmployeeStaff, each of which extends the EmployeePerson class. The main program creates objects of type EmployeeManager and EmployeeStaff and prints those objects.

Specifications
Define the EmployeeManager and EmployeeStaff classes in EmployeeManager.cpp and EmployeeStaff.cpp respectively.
Make the EmployeeStaff class override the EmployeePerson class' PrintInfo function and print all the fields from the EmployeeStaff class.
Make the EmployeeManager class override the EmployeePerson class' printInfo function and print all the fields from the EmployeeManager class.
Run the program and verify the output includes the manager and staff information.

Required Employee interfaces
EmployeePerson.h and EmployeePerson.cpp contain the EmployeePerson class declaration and definition. EmployeeManager.h and EmployeeStaff.h contain the EmployeeManager and EmployeeStaff class declarations. Use these to create the class definitions in EmployeeManager.cpp and EmployeeStaff.cpp. The EmployeePerson.h, EmployeePerson.cpp, EmployeeManager.h, and EmployeeStaff.h files cannot be changed.

The main() function
The main() function to test your classes is in EmployeeMain.cpp and cannot be changed.

For the main() function given, the output is:

Name: Michele, Department: Sales, Birthday: 03-03-1975, Salary: 70000, Staff managed: 25
Name: Bob, Department: Sales, Birthday: 02-02-1980, Salary: 50000, Manager: Michele

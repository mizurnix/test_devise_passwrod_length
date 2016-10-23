# @minimum_password_length does not work in devise/registrations/edit view

@minimum_password_length is accessible in registrations/edit view, but only if the form is submitted without errors.

User goes to registrations/edit page and it's there:

![image 7](https://cloud.githubusercontent.com/assets/10742145/19351112/b6b5133e-915a-11e6-8afc-c4b5db2ce581.png)

User submits incomplete form and after the redirect, it's gone:

![image 8](https://cloud.githubusercontent.com/assets/10742145/19351203/168feef0-915b-11e6-934e-a04661775c46.png)

This test application is running here: http://testdevisepasswordlength.herokuapp.com/ 

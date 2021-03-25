# Answers for Task 3

## Task 3.a.
<br>
1. Class Student

* For the updateName method it is better to use the setter method setFirstName to assign
  the first name for reducing code repetition/duplication.
* Add another setter method setLastName like the setter method setFirstName for the code
  readability and efficiency.

2. Class StudentListener

* Use StudentListener() as a constructor which instantiate student instead of using 
  StudentListener(Student s) this is because of memory management, time consumption 
  and constructor overloading.
* Chane the name of method updateName(String firstName, String lastName, String address)
  to updateDetails because for code readability and this method updates the address not 
  only the name.
* Remove the method updateName(String firstName, String lastname) and use the method 
  updateDetails instead because of code repetition/duplication.
</br>
## Task 3.b.
<br>
By using the command "git log" there was only 1 commit made each for both branches which are:

* Master Branch - cff390ad7ae5d69d7031ce42510ee37907a5a3a4
* Develop Branch - 9f08d1221d62e9010171c1b5c71ccb9f1c9aa5a6
</br>

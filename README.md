# Student-REST-API-Testing

## ***How to run this project***
- Clone this project
- Open with Postman / Command Shell
- Run Command:  


newman run Studentsdetails.postman_collection.json -e Studentsdetails.postman_environment.json

- Run Command for Report: 



newman run Studentsdetails.postman_collection.json -e Studentsdetails.postman_environment.json -r cli,htmlextra


## ***Technology used***
- Postman
- Newman

## ***Prerequisite***
- Jdk
- Node Js
- Newman
- Html Report Library

## ***Newman and Report Installation Process***
- Newman Install Command:
```console
npm install -g newman
```
- Newman Html Report Install Command:
```console
npm install -g newman-reporter-htmlextra
```

## ***API Documentation***
- https://documenter.getpostman.com/view/27187339/2s93ebUWmr

## Test case list
1. ### ***Get Student***
	> In this section we checked the whole pre-defined datasets of students and validate the following test result:
	1. > Status Code

2. ### ***Create Student***
	> In this section we created a dataset giving information in the request body and validate the following test result:
 	1. > Status Code

3. ### ***Get Specific Student***
  	> In this section called a specific student using his/her id and validate the following field values:
  	1. > Status Code
 	2. > ID
 	3. > First Name
 	4. > Middle Name
 	5. > Last Name
 	6. > Date of Birth

4. ### ***Create Technical Skills***
	> In this section we added technical skills of the student by calling his/her id and validate the following test result:
 	1. > Status Code
	
5. ### ***Create Student Address***
	> In this section we added the address of the student by calling his/her id and validate the following field values:
	1. > Status Code
 	2. > Status
 	3. > Message

6. ### ***Final Student Details***
	> In this section we called the student using his/her id and validate the following field values:
	1. > Status Code
 	2. > Language
	3. > Year of Experience
	4. > House Number
	5. > City
	6. > Country
	7. > Mobile
	8. > Current Address
	
## ***Newman Report Summary***
![Screenshot (271)](https://github.com/Swarna2509/studentdetails/assets/72212832/6b660a89-acc9-4e97-8407-5cb269a3d1a6)
![Screenshot (272)](https://github.com/Swarna2509/studentdetails/assets/72212832/2f0f71ad-fb0a-4272-b4e9-09a43929d731)

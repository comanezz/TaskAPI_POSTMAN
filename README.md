# TaskAPI_POSTMAN

It is a project to show off my understanding of REST API and used POSTMAN for test.

Used Django to design it.

## Issue encountered
### 1

![Error create user](imgs/Error_creating_user.png)

- Error creating users because I used space in the username and forgot the password field. Issue corrected. By removing the space in username and adding a password. **SOLVED**

![Successful user creation](imgs/Success_creating_user.png)

### 2
- Failed to create a task because the URL in my URLs DJANGO was incorrect. I forgot the slash (’/’) in api/. 
![Fail create task](imgs/Fail_createTask.png)

![Fail URL](imgs/issue_url_found.png)

- Also, forgot to add in headers the Authentication Token. **SOLVED**

![Successful creation task](imgs/AddTaskSuccess.png)

## Successful Other Tests
### Successful Login
![Successful Login](imgs/Login_Success.png)

### Sucessful Get List
![Successful Get List](imgs/Retrieve_all_list.png)

### Sucessful Update List
![Successful Update](imgs/UpdateTask.png)

### Sucessful Delete List
![Successful Deletion](imgs/DeleteSuccessful.png)

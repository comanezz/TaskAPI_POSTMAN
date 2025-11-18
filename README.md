# TaskAPI_POSTMAN

It is a project to show off my understanding of REST API and used POSTMAN for test.

Used Django to design it.

## Issue encountered

![Error create user](imgs/Error_creating_user.png)
- Error creating users because I used space in the username and forgot the password field. Issue corrected. By removing the space in username and adding a password. **SOLVED**
![Successful user creation](imgs/Success_creating_user.png)

![Fail create task](imgs/Fail_createTask.png)
![Fail URL](imgs/issue_url_found.png)
- Failed to create a task because the URL in my URLs DJANGO was incorrect. I forgot the slash (’/’) in api/. Also, forgot to add in headers the Authentication Token. **SOLVED**
![Successful creation task](imgs/AddTaskSuccess.png)

## Successful Other Tests
![Successful Login](imgs/Login_Success.png)
![Successful Get List](imgs/Retrieve_all_list.png)
![Successful Update](imgs/UpdateTask.png)
![Successful Deletion](imgs/DeleteSuccessful.png)

# VodafoneTask
I Created .net core Mvc Project with frontend to let you test all features with UI
# Tools Needed 
(Visual Studio, .net 8)
# Project Structure 
  Solution has 4 Projects in it
    1-Domain (Contains Database Entity).
    2-Infrastructure (Contains Mapping,ModelViews,DatabaseOperations Service).
    3-Services (All Project Services).
    4-VodafoneTask(# Main Project).

#(Vodafone Task) Main Part in the Solution
* has controllers, View, and every view has 2 files one for css styling and the other for JavaScript both 2 files have the same name as view
* Every Controller has service, views folder,ModelView folder, css file, JavaScript file with the same name

# Step by step to run the Project
1- Download Visual Studio(.net core 8 Will be included Automatically).

2- If You Already Have Visual Studio.

    - open visual Studio installer (Download .net core 8).
![1](https://github.com/user-attachments/assets/18f5fe37-a7b2-4d72-b481-02206d7fe537)

3- Open Visual studio and clone the project.
![2](https://github.com/user-attachments/assets/8e0a080f-1f77-437c-83d7-7f594886752d)

4- in file appsettings.json change the connection string to your own sql server.
  - you don't have to create new database just set any name for the database in the connection string
  - the project will automatically create new database. 
![3](https://github.com/user-attachments/assets/63a41197-1c1f-4cc6-93e4-db733deb064b)

5- open package manager console from (View) tab on the top.
![Screenshot (4)](https://github.com/user-attachments/assets/0998c652-da72-471e-b8b8-ed9e2c2c4924)

6- write the following command: dotnet restore
![6](https://github.com/user-attachments/assets/027b67f7-9d3e-48cf-803b-8db9f669c3fb)

7- write the following command: update-database 
  - remember to change the default project in package manager console to (Infrastructure Project) as this project contains database files
![7](https://github.com/user-attachments/assets/25589063-b3fd-4bba-8239-50fda79ce450)

8- now you can run the project on IIS or HTTP (Don't use HTTPS) (Live Images).
![10](https://github.com/user-attachments/assets/048f605c-1566-42da-8111-35aa45170907)
![11](https://github.com/user-attachments/assets/aed6a1e6-3a7d-4bae-83ec-827c6b7bb82f)
![12](https://github.com/user-attachments/assets/902cbf15-d3b2-4d6f-8b2a-45e6ebbc6d2b)




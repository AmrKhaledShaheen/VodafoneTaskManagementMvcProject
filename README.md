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
    
      ![1](https://github.com/user-attachments/assets/24fe31bf-cb47-42d4-9ae8-728f3fff7736)
3- Open Visual studio and clone the project.

4- in file appsettings.json change the connection string to your own sql server.

5- open package manager console from (View) tab on the top.

6- write the following command: update-database.

7- now you can run the project.



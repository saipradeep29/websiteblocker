# websiteblocker
A python application that restricts entry into websites during  certain time..
Libraries used in this application are time and datetime for getting the current time of the day and also to give a delay in responding.

We first decide a duration in which we want to block the websites. We also decide which websites have to be blocked. Then we check if our current time is in the duration. If it is then we write to the hosts file local machine ip address and the website(domain) name. If it is outside the duration then we erase the file contents.
# Note
Not all systems will have host files at same place depending on operating-system we need to find 

For  Windows path is– “C:\Windows\System32\drivers\etc\hosts”

For Linux path is – “/etc/hosts”

For Mac OS X path is– “/private/etc/hosts”

# Getting started
run the file using python .add the websites that you want to block in website list 
every time you neednot to run script to automate that

go to >task_scheduler >create_task> mark the run with high privilage >ok
![wb1](https://user-images.githubusercontent.com/105792542/169052862-d63458db-150c-418c-ab0c-c872e3aa6d49.JPG)


new trigger> begin_task :- startup>ok
![wb2](https://user-images.githubusercontent.com/105792542/169052946-4c5da65f-d219-4011-ad80-2e4eb501616a.JPG)


actions> start program>program script :- you need to add script with extension .pyw
![wb3](https://user-images.githubusercontent.com/105792542/169052999-96ce7662-62b6-4f7e-b734-e129e776b00b.JPG)


conditions> uncheck all

![wb4](https://user-images.githubusercontent.com/105792542/169053045-e363cb6c-d925-4030-b6bb-1f9e47f511b2.JPG)

# RUN
run the tasker ..and here it goes

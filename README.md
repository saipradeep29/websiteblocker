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


new trigger> begin_task :- startup>ok


actions> start program>program script :- you need to add script with extension .pyw



conditions> uncheck all


# RUN
run the tasker ..and here it goes

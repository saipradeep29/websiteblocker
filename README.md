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
/add path of hosts  to host_path in code

example :hosts_path="C:\Windows\System32\drivers\etc\hosts"

/add websites you want to block in website_list in the code

 example :website_list=["instagram.com","spankbang.com"]
 
/run the script using python

# Automate script

//go to >task_scheduler >create_task> mark the run with high privilage >ok
![wb11](https://user-images.githubusercontent.com/105792542/169060173-18954d3c-e32c-4429-82fa-5073902d13cc.png)



//new trigger> begin_task :- startup>ok
![wb12](https://user-images.githubusercontent.com/105792542/169060794-41603cc6-ea25-4ae1-96b8-72020fad3cbd.png)



//actions> start program>program script :- you need to add script with extension .pyw
![wb13](https://user-images.githubusercontent.com/105792542/169060849-cc7d0dbd-1b18-464d-a336-d2cb661088b8.png)



//conditions> uncheck all


# RUN
run the tasker ..and here it goes

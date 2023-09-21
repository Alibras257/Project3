### Web Stack Implementation Project (Lemp Stack)



- The First step is to run Sudo Apt Update command which was done in the image Below.


![Alt text](<images/Screenshot 2023-09-17 214535.png>)



- Then I install nginx putting -y for quick install to avoid Yes/No prompt



![Alt text](<images/Screenshot 2023-09-17 214749.png>)




- Then I checked the status of the nginx with **systemctl** command and it's active running.



![Alt text](<images/Screenshot 2023-09-17 214851.png>)




- Then i run the **curl** command with the localhost to display the content after setting the inbound settings under security on AWS EC2 instance, i forgot to take a snap of that.



![Alt text](<images/Screenshot 2023-09-17 215027.png>)




- After that i run the **curl -s** command and paste my EC2 IP address on the browser to get the following.. to be sure the nginx is active and running fine





![Alt text](<images/Screenshot 2023-09-17 215823.png>)




- Then i move on to installing mysql



![Alt text](<images/Screenshot 2023-09-17 220153.png>)



- Then I enetered into mysql but it was not asking for password as seen in the image below



![Alt text](<images/Screenshot 2023-09-17 220323.png>)





- I then exited and set a root password to prompt for password for next login...





![Alt text](<images/Screenshot 2023-09-17 221519.png>)




- I then changed the root password to my desired password then set the rules in the following 2 images then i exit mysql




![Alt text](<images/Screenshot 2023-09-17 221940.png>)


![Alt text](<images/Screenshot 2023-09-17 222342.png>)



- I tried to login to mysql and I have to prompt it to ask for password so i can have access, I enetered the new password and i was able to login




![Alt text](<images/Screenshot 2023-09-17 222424.png>)



The I installed php and **ls** the content then **cat** the file in the content to see what is inside, the 2 images below shows that



![Alt text](<images/Screenshot 2023-09-17 222941.png>)



![Alt text](<images/Screenshot 2023-09-17 223515.png>)



- After that i created a new directory named ProjecyLemp and changed the USER and echo what is conatined in the USER


![Alt text](<images/Screenshot 2023-09-17 224618.png>)




- I then check if the syntax is ok 



![Alt text](<images/Screenshot 2023-09-17 225358.png>)




- I go back to my browser to refresh and got the following


![Alt text](<images/Screenshot 2023-09-17 225412.png>)



- I forgot to mention I used I created a php file named info and *nano* command to edit the content of the contect in ProjectLemp 


- I changed the contect with nano command and go back to my browser to add .php to get the second image below.



![Alt text](<images/Screenshot 2023-09-17 230823.png>)



![Alt text](<images/Screenshot 2023-09-17 230838.png>)





- Then i entered mysql again to create a table and put content to be dispalayed on the browser which is todo list... The following images explains that



![Alt text](<images/Screenshot 2023-09-17 231755.png>)

![Alt text](<images/Screenshot 2023-09-17 232043.png>)


![Alt text](<images/Screenshot 2023-09-17 232227.png>)




- I the n go back to my browser and add todo.php to the ip address and get the following..


![Alt text](<images/Screenshot 2023-09-17 232242.png>).


*That was all about ProjectLemp and I hope I am explanatory enough, Please pardon me as I dont know why I couldn't find some images again.*















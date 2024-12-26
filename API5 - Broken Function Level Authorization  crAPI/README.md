# API-Testing-Documentary
upload a vedio in my profile
![alt text](image.png)
we can change video , change video Name and Share vedio with community  
![alt text](image-1.png)
but can't delete the video 
so let's start the burpsuit 
change the vedio name
![alt text](image-2.png)
now send it to repeater
![alt text](image-3.png)
![alt text](image-4.png)
 
Change put request to Options request to know that which request we can 
![alt text](image-5.png)
so we can see that we can able to request  GET,HEAD,PUT,DELETE,OPTIONS

so lets change Options to delet
![alt text](image-6.png)
We can't the delete the video due to it only able to deleted my admin 
so lets privilege acceleration 
change user to admin
![alt text](image-7.png)
![alt text](image-8.png)



















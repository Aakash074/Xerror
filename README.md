# Xerror


Xerror is an automated penetration tool , which will helps security professionals and non professionals to automate their pentesting tasks. Xerror will do all tests and, at the end generate two reports for executives and analysts.

After completion of Xerror, it will will provides GUI and internally it supports openVas, nessus and nexpose for vulnerability scanning, Metasploit for exploitation and gives GUI based options after successful exploitation e.g Meterpreter sessoins.
Building in python as major. 


How to use this porject: 
 1.Activate virtual enviroment by following command 
      souce env/bin/activate
 2. Start redis server
      service redis-server start
 3. start python srver 
      1. cd xerror 
      2. python mana.py runserver 
 4. start celery server 
      1. cd xerror 
      2. celery -A xerror worker -l info 
 5. start msfrpc server 
      msfrpcd -P 123 -S -a 127.0.0.1
 6. start openvas server for default set OMP server credientials to admin@admin 127.0.0.1 9392 
 
 
 You are goog to go 
 
 This is xerror Beta version, soon complete version will be uploaded with complete explanation and detail of each step ...   
 
 ![alt text](https://i.imgur.com/oJQH6ax.png)
 
 
![alt text](https://i.imgur.com/RTyPiiZ.png)

![alt text](https://i.imgur.com/yLMMNC2.png)


![alt text](https://i.imgur.com/K7k2uRu.png)

![alt text](https://i.imgur.com/dnDWm0O.png)

![alt text](https://i.imgur.com/pn0evVH.png)




![alt text](https://i.imgur.com/tMo0B5S.png)

![alt text](https://i.imgur.com/65JUi9y.png)
 
 ![alt text](https://i.imgur.com/BIqlXr9.png)
 
 
 ![alt text](https://i.imgur.com/dV3NuRv.png)
 
 ![alt text](https://i.imgur.com/W9bBejm.png)
 
 
 
 
 
 
 
 

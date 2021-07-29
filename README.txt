This is a python and html used project made by Nihal S Raj @blackhatdog

#OpenSource

What is this ?

Th is is an open source project which can be used to start a server on a network . This server provides a few online books with a GUI

---------------------------------------------

Requirements:
Windows(for NetLib host+.cmd file only)
Python 3
Lan Network

---------------------------------------------
username : userx
password:user
---------------------------------------------
What to do ?

The network hosting is done by a python in built module called http.server .


---------------------------------------------
Windows :

1.Navigate to Netlib/templates in file explorer 
2.Click on the Netlib_Host+.cmd 

3. a window like this should appear
(winpic.jpg)
4. Go to browser on any device 
5. go to http://<ip address of hosting computer>:8080
--------------------------------------------------------
how to find ip address on windows?

netlibhost+ is proggrammed to show ip details of the running computer
in winpic.jpg , in the blurred part (blurred in image for security reasons) under ipv4 address you will find your ip adress


---------------------------------------------
Linux 
*not tested 
*python required 

1. open the netlib folder like in windows 
2. open terminal 
3. enter python -m http.server 8080 
4. go to http://<ip address of hosting computer>:8080



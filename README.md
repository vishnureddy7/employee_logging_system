<h1>Efficient Employee Logging System</h1>

step1  --> First of all we need Arduino RFID scanner

step2  --> Sample RFIDs to scan

step3  --> Arduino is need to be installed

step4  --> Python3.7 need to be installed

step5  --> Then do "python -m pip install -r requiremets.txt" to install the python libraries

step6  --> MySQL server need to be installed and running

step7  --> Tables need to be created as in the database in schema

step8  --> Make sure that crd folder is created for send emails with email.crd, password.crd and host.crd.<br/>
&nbsp;&nbsp;&nbsp;&nbsp;email.crd should contain email in base64 format<br/>
&nbsp;&nbsp;&nbsp;&nbsp;password.crd should contain password in base64 format<br/>
&nbsp;&nbsp;&nbsp;&nbsp;host.crd should contain host address in base64 format<br/>
		  
step9  --> Connect the RFID scanner and open Arduino code file and execute it

step10 --> Now the scanner can read the cards

step11 -> Open the Python code and run it in Python shell

step12 -> That's it the we can scan the ids and the program will start doing its work in the background  by displaying some logs and errors if any

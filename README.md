# EX01 Developing a Simple Webserver
## Date:25/08/2006

## AIM:
To develop a simple webserver to serve html pages and display the list of protocols in TCP/IP Protocol Suite.

## DESIGN STEPS:
### Step 1: 
HTML content creation.

### Step 2:
Design of webserver workflow.

### Step 3:
Implementation using Python code.

### Step 4:
Import the necessary modules.

### Step 5:
Define a custom request handler.

### Step 6:
Start an HTTP server on a specific port.

### Step 7:
Run the Python script to serve web pages.

### Step 8:
Serve the HTML pages.

### Step 9:
Start the server script and check for errors.

### Step 10:
Open a browser and navigate to http://127.0.0.1:8000 (or the assigned port).

## PROGRAM:
```
<!doctype html>
<html>
<head>
<title> My Web Server</title>
</head>
<body>
<h1>
<table align="center" border="1" bgcolor="cyan" cellpadding="10">
    <caption>LIST OF PROTOCOL IN TCP/IP PROTOCOLSUITE </caption>
    <tr ><th bgcolor="brown">S.No.</th><th bgcolor="brown">Name of the layers</th><th bgcolor="brown"> Name of the protocol</th></tr>
    <tr><td bgcolor="red">1</td><td bgcolor="red">Application Layer</td><td bgcolor="red">HTTP,FTP,DNS,Telnet & SS <br> </td></tr>
    <tr><td bgcolor="pink">2</td><td bgcolor="pink">Transport Layer </td><td bgcolor="pink">TCP & UDP <br> </td></tr>
    <tr><td bgcolor="red">3</td><td bgcolor="red"> Network Layer </td><td bgcolor="red">IPV4/IPV6 <br> </td></tr>
    <tr><td bgcolor="pink">4</td><td bgcolor="pink">Link Layer</td><td bgcolor="pink">Ethernet<br> </td></tr>
</table>
   
</h1>
</body>
</html>
```
## OUTPUT:
![alt text](<Screenshot (1).png>)

## RESULT:
The program for implementing simple webserver is executed successfully.
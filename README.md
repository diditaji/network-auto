<h1>Network Automation Backup </h1>
<p>This script will try login to your Cisco Switch and export the output to .docx.<br><br>
Network Automation Menu : </p>

1.Show environment-docx<br>
2.Show running-config-docx<br>
3.Show version-docx<br>
4.Show cpu-docx<br>
5.Show all-docx<br>
6.Exit<br>

Enter your choice:<br>

<h2>How to use</b2>
<p>First step, you must change the username which you will be used for login to each switch inside net-auto.py.
<p>username = 'xxxxxx'
<p>Then, fill ipaddress.txt with list of IP Address of your switch, save it. Please make sure you have pyhton library installed : netmiko, pandas and docx
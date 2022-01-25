<h1>Network Automation Backup </h1>
<p>This script will try login to your Cisco Switch and export the output to .docx.<br><br>
Network Automation Menu : </p>

Network Automation Menu :<br>

1.Show Environment >> output : docx<br>
2.Show Running Config >> output : docx<br>
3.Show Version >> output : docx<br>
4.Show CPU >> output : docx<br>
5.Show Env, Run, Ver and CPU >> output : docx<br>
6.Show Config PA >> output : docx<br>
7.Show Running Config ASA >> output : docx<br>
8.Show Version Cisco Switch >> output : xlsx<br>
9.Exit<br>

Enter your choice:<br>

<h2>How to use</h2>
<p>First step, you must change the username which you will be used for login to each switch inside net-auto.py.
<p>username = 'xxxxxx'
<p>Then, fill ipaddress.txt with list of IP Address of your switch, save it. Please make sure you have pyhton library installed : netmiko, pandas and python-docx

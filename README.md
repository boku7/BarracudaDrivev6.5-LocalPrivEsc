## Exploit Title:   BarracudaDrive v6.5 - User->System - Local Privilege Escalation
### Exploit Author:  Bobby Cooke (boku) & Adeeb Shah (@hyd3sec) 
+ CVSS Base Score: 8.8 | Impact Subscore: 6.0 | Exploitability Subscore: 2.0
+ CVSS Vector: AV:L/AC:L/PR:L/UI:N/S:C/C:H/I:H/A:H
+ CWE-276: Incorrect Default Permissions
+ CWE-732: Incorrect Permission Assignment for Critical Resource
#### Vulnerability Description:
+ Insecure Service File Permissions in bd service in Real Time Logics BarracudaDrive v6.5 allows local attackers to escalate privileges to admin via replacing the bd.exe file and restarting the computer where the malicious code  will be executed as 'LocalSystem' on the next startup automatically.
#### Vendor Homepage: https://barracudaserver.com/
#### Software Link:   https://download.cnet.com/BarracudaDrive/3001-18506_4-10723210.html

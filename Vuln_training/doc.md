<h1>Site : http://www.vulntraining.co.uk/ </h1>

<b>First Flag</b>: Visible in source file
![alt text](https://github.com/WhiteWolf2077/CTF_Challenge/blob/master/Vuln_training/Pictures/2020-06-08_19-52.png)

<b>Second Flag</b>: Accessing robots.txt will lead to secret directory

![2nd flag](https://github.com/WhiteWolf2077/CTF_Challenge/blob/master/Vuln_training/Pictures/2020-06-08_20-01.png)

<b>Third Flag</b>: After much enumeration we found out a .git/config file which leads us to a url = https://github.com/vuln-tr4in1ng-projects/website_framework.git

![3rd flag](https://github.com/WhiteWolf2077/CTF_Challenge/blob/master/Vuln_training/Pictures/2020-06-08_20-32.png)

<b>Fourth Flag</b>: Use burp suite to intercept request to /server and the flag will be visible in response

![4th flag](https://github.com/WhiteWolf2077/CTF_Challenge/blob/master/Vuln_training/Pictures/2020-06-09_05-09.png)

<b>Fifth Flag</b>: From the request you get a secret url link, go there and get the flag

![5th flag](https://github.com/WhiteWolf2077/CTF_Challenge/blob/master/Vuln_training/Pictures/2020-06-09_05-12.png)

<b>Sixth flag</b>: Subdomain finder leads us to a domain: <i>c867fc3a.vulntraining.co.uk</i>

<b>Seventh Flag</b>: ANother one found while bruteforcing for password on <i>billing.vulntraing.co.uk</i>

![7th flag](https://github.com/WhiteWolf2077/CTF_Challenge/blob/master/Vuln_training/Pictures/2020-06-09_05-52.png)

<b>Eighth Flag</b>:

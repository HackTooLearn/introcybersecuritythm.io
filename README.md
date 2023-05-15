<h1>Hack to Learn</h1> 
  <h2>Cyber Security Learning</h2>
  
Getting started with TryHackMe can be scary! Not knowing where to click, or what you are allowed to click on, what to type, where to type, what to do next??? 

Hack To Learn is here to point out some of the basics to get you going on your Cyber Security path. There is absolutely no harm in copying & pasting in order to get things completed. Understanding what is going on, or how it is working is the most important lesson. Break it down into simple steps / stages in order to grasp or understand. There are YouTube video walk throughs available - clicking on the link will take you to that particular Rooms video on YouTube. 

#cybersecurity #tryhackme #walk-throughs #ethicalhacker #penetrationtester
  

## MAKE GOOD NOTES

<br>

<h1>Intro to Offensive Security ~ (TryHackMe)</h1>

<br>

## YouTube walk-through video 
[YouTube video link](https://youtu.be/-cYmjT0kYNE)


## Commands / Steps

- click green `start button`
- read the task contents for Task 1
- open up the terminal
- type the following below command into the terminal
- `gobuster -u http://fakebank.com -w wordlist.txt dir`
- gobuster finds 2 x directories
- `/images & /bank-transfer`
- go to the browser & tack the directories found onto the end of the URL to see what appears, one at a time
- `/images` returns 404 not found
- `/bank-transfer` returns an admin portal to transfer money
- transfer from `*2276*`
- to account `*8881*`
- amount of `*$2000*`
- click `send money`
- you should see --->  ==transfer successful==
- return to fakebank.com homepage by deleting /bank-transfer in the URL & hit enter
- there is the flag!  _*THM{}*_

<br>

## _Congratualtions on finding the Flag!_

#gobuster #fakebank #offensivesecurity 

<br>

<br>

---

<br>

<h1>Intro to Defensive Security ~ (TryHackMe)</h1>

<br>

## YouTube walk-through video 
[YouTube video link](https://youtu.be/AzWVHeIqzAU)


## Commands / Steps for Task 3

- click green `view site` button
- scroll over the list of alert logs
- one of them highlights `red`
- make note of the red `ip address` 
- click on the `red` alert log
- ip scanner opens up 
- enter the copied `ip address` from the `red` alert log
- click `submit`
- read through
- click next in `blue`
- read through
- select which team member -- (for the task you're part of a soc team)
- soc team lead -- [will griffin]
- enter copied `ip address` into firewall block list
- click block ip address
- there is the flag!  _`*THM{}*`_ 

<br>

## _Congratualtions finding the Flag!_

#dfir #soc #ransomware #malicious #tryhackme #defensivesecurity

<br>

<br>

---

<br>

<h1>Web Application Security ~ (TryHackMe)</h1>

<br>

### YouTube walk-through video 
[YouTube video link](https://youtu.be/W7Bwfq7axoE)


## Commands / steps 

- click green `view site` button
- click on planned shipments tab
- orders of tyres all mixed up
- click on `your activity` tab
- see employee roddy user_id=11 appear
- go to browser url by `user_id=11` & change this to `user_id=10`
- hit `enter`
- continue doing this from 11 - 5
- number 9 stands out > alya database administrator
- click the revert button/s under action until all gone
- there is the flag!  _`*THM{}*`_

<br>

## _Congratualtions finding the Flag!_

#webapp #userid #idor 

<br>

<br>

---

<br>







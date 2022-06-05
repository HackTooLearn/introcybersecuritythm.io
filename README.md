# Hack to Learn! 

<p> 
  
It can be scary in the beginning, not knowing where to click, or what do to do next?? Pointing out some of the basics to get you on your path. No harm in copying & pasting, in order to get things completed. Understanding what is going on,  or how it is working is the most important lesson. 

#cybersecurity #tryhackme #walk-throughs #ethicalhacker #penetrationtester
  
</p>

<br>

## Intro to Offensive Security ~ (TryHackMe)

<br>

## Commands / steps

- click green `start button`
- read the task contents for Task 1
- open up terminal
- type the following command in terminal:
- `gobuster -u http://fakebank.com -w wordlist.txt dir`
- see 2 x directories found by gobuster
- `/images & /bank-transfer`
- go to the browser & tack the directories found onto the end to see what appears, one at a time
- `/images` returns 404 not found
- `/bank-transfer` returns an admin portal to transfer money
- transfer from `*2276*`
- to account `*8881*`
- amount of `*$2000*`
- click `send money`
- should see -- =transfer successful=
- return to fakebank.com homepage by deleting /bank-transfer in the URL & hit enter
- there is the flag!  _*thm{}*_

<br>

## _Congratualtions finding your 1st Flag!_



